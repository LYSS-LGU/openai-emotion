# 💭 기분 분석 서비스

React로 만든 OpenAI 기반 기분 분석 서비스입니다. 사용자가 현재 기분을 입력하면 AI가 감정을 분석하고 따뜻한 조언을 제공합니다.

## 설치 및 실행

1. 의존성 설치:

```bash
npm install
```

2. OpenAI API 키 설정:

   - 프로젝트 루트에 `.env` 파일을 생성하고 다음 내용을 추가하세요:

   ```
   REACT_APP_OPENAI_API_KEY=your_openai_api_key_here
   ```

   - `your_openai_api_key_here` 부분을 실제 OpenAI API 키로 교체하세요.
   - OpenAI API 키는 [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys)에서 발급받을 수 있습니다.
   - **중요**: `.env` 파일은 절대 Git에 커밋하지 마세요! API 키가 노출될 수 있습니다.
   - OpenAI API 키는 [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys)에서 발급받을 수 있습니다.
   - **중요**: `.env` 파일은 절대 Git에 커밋하지 마세요! API 키가 노출될 수 있습니다.

3. 개발 서버 실행:

```bash
npm start
```

4. 브라우저에서 [http://localhost:3000](http://localhost:3000)으로 접속하세요.

## 기능

- **감정 분석**: 사용자의 기분을 AI가 분석
- **개인화된 조언**: 상황에 맞는 따뜻한 조언 제공
- **아름다운 UI**: 그라데이션 배경과 글래스모피즘 디자인
- **반응형 디자인**: 모바일과 데스크톱 모두 지원

## 사용법

1. 텍스트 영역에 현재 기분을 자유롭게 표현하세요
2. "기분 분석하기" 버튼을 클릭하세요
3. AI가 당신의 기분을 분석하고 조언을 제공합니다

## 예시 입력

- "오늘 회사에서 상사한테 혼났는데, 집에 와서도 계속 신경 쓰여요..."
- "친구들과 재미있게 놀았는데, 갑자기 외로워져요"
- "시험 결과가 좋아서 기분이 너무 좋아요!"

## 주의사항

- OpenAI API 키가 필요합니다
- API 사용량에 따라 비용이 발생할 수 있습니다
- 인터넷 연결이 필요합니다
- 민감한 개인정보는 입력하지 마세요
