![image](https://github.com/user-attachments/assets/60fd3eff-fe51-4917-b90e-b87fa62c17ca)
![image](https://github.com/user-attachments/assets/9106b157-22ac-476c-990e-fa0a135eda87)

 이를 바탕으로 한국어 버전의 **README.md** 파일을 업데이트하여, 사용자가 해당 한국어 페이지로도 쉽게 접근할 수 있도록 안내할 수 있습니다.

다음은 한국어 버전의 GitHub **README.md** 파일 업데이트입니다.

### **업데이트된 한국어 README.md**

```markdown
# AI Judge GPT - 판결문 생성기

AI Judge GPT는 사용자가 입력한 사건에 대해 OpenAI GPT 모델을 기반으로 판결문을 생성하는 웹 애플리케이션입니다. 이 애플리케이션은 사건 설명을 입력하고, 사용자가 원하는 GPT 모델을 선택하여, AI가 실제 판사의 역할을 하여 사건에 대한 판결을 내리는 기능을 제공합니다.

## Features
- 사건 설명에 따라 자동으로 판결문 생성
- OpenAI의 GPT 모델을 활용하여 유죄/무죄 판결과 적절한 법적 처벌 결정
- 다양한 GPT 모델 선택 가능 (`gpt-3`, `gpt-3.5-turbo`, `text-davinci-003`, `text-curie-001`, `text-babbage-001`)
- 사용자 지정 API 키로 OpenAI API 호출
- 깔끔한 UI와 판결문 출력 디자인

## Demo
AI Judge GPT의 한국어 버전 데모를 확인하려면 [여기](https://hwkims.github.io/AI-Judge/ko.html)를 클릭하세요.

## Requirements
- OpenAI API Key: AI 모델을 사용하려면 [OpenAI](https://beta.openai.com/signup/)에서 API 키를 발급받아야 합니다.
- 최신 웹 브라우저: 이 웹 애플리케이션을 실행하려면 최신 웹 브라우저가 필요합니다.

## Installation
1. 리포지토리를 로컬 머신에 클론합니다:
   ```bash
   git clone https://github.com/hwkims/AI-Judge.git
   ```

2. `index.html` 파일을 브라우저에서 엽니다.

3. OpenAI API 키를 입력 필드에 입력하여 판결문 생성을 시작합니다.

## Usage
1. **OpenAI API Key 입력**: OpenAI 서버에 요청을 보내려면 API 키가 필요합니다.
   
2. **사건 설명 입력**: 판결을 내릴 사건을 설명합니다. 예: "피고인은 반란을 선동했다는 혐의를 받고 있습니다."

3. **GPT 모델 선택**: 원하는 GPT 모델을 선택합니다. 선택 가능한 모델:
   - `gpt-3.5-turbo`
   - `gpt-3`
   - `text-davinci-003`
   - `text-curie-001`
   - `text-babbage-001`
   
4. **판결문 생성**: 필요한 정보를 입력한 후 "Generate Verdict" 버튼을 클릭하여 AI Judge GPT가 판결을 생성하도록 합니다.

5. **판결문 보기**: 생성된 판결문이 화면에 표시됩니다. 피고가 유죄인지 무죄인지, 유죄라면 적절한 처벌이 무엇인지 포함됩니다.

## Example Input
**사건 설명**: "정치 지도자가 반란을 선동하고 정부를 전복하려 시도했다."

**GPT 모델**: `gpt-3.5-turbo`

**API Key**: OpenAI API 키

**결과**: 애플리케이션은 판사의 판결을 생성합니다.

## License
이 프로젝트는 MIT 라이선스 하에 제공됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하십시오.

## Acknowledgements
- [OpenAI](https://openai.com/)에 감사드립니다. GPT 모델을 제공해주셔서 감사합니다.
- 이 프로젝트는 AI 기반의 법률 시뮬레이션을 위한 프로젝트입니다.

## Contact
문의사항이나 기여 관련 사항은 이슈를 열거나 직접 연락해 주세요.

**GitHub Username**: [hwkims](https://github.com/hwkims)
```

### 주요 변경 사항:
1. **한국어 데모 링크 추가**:
   - 한국어 버전의 실제 데모 페이지 링크를 **[여기](https://hwkims.github.io/AI-Judge/ko.html)**로 추가했습니다.
   
2. **기타 내용**:
   - 나머지 내용은 영어 버전과 동일하게, 사용자가 OpenAI API 키를 입력하고 사건 설명을 제공하며, 모델을 선택하여 판결문을 생성하는 방법을 안내하고 있습니다.

### 요약:
이 README.md 파일은 사용자가 프로젝트를 쉽게 이해하고 설치할 수 있도록 돕습니다. 또한, 한국어 데모 링크를 통해 사용자는 실제로 작동하는 예제를 확인할 수 있습니다. GitHub 페이지에서 제공하는 한국어 버전 데모 링크도 바로 접속할 수 있게 되었습니다.



알겠습니다! 이제 영어 버전의 **README.md** 파일을 업데이트하여, 사용자가 AI Judge GPT의 영어 버전 데모 페이지로 쉽게 접근할 수 있도록 안내하겠습니다.

### **Updated English README.md**

```markdown
# AI Judge GPT - Verdict Generator

AI Judge GPT is a web application that generates legal verdicts based on the case description provided by the user. The application leverages OpenAI's GPT model to simulate a judge's decision, including guilty/not guilty verdicts and appropriate legal punishments.

## Features
- Automatically generates verdicts based on the case description.
- Uses OpenAI GPT models to determine guilty/not guilty and recommend legal punishment.
- Select from various GPT models (`gpt-3`, `gpt-3.5-turbo`, `text-davinci-003`, `text-curie-001`, `text-babbage-001`).
- Allows users to input their own OpenAI API key to make requests to the OpenAI server.
- Clean UI and verdict output design.

## Demo
Check out the live demo of AI Judge GPT in English on [GitHub Pages](https://hwkims.github.io/AI-Judge/).

## Requirements
- OpenAI API Key: To use the AI model, you need an API key from [OpenAI](https://beta.openai.com/signup/).
- A modern browser to run the web application.

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/hwkims/AI-Judge.git
   ```

2. Open the `index.html` file in your browser.

3. Enter your OpenAI API key into the provided input field to start generating verdicts.

## Usage
1. **Enter OpenAI API Key**: You need to input your OpenAI API key to make requests to the OpenAI server.
   
2. **Enter Case Description**: Describe the case for which you need the verdict. For example, "The defendant is accused of inciting rebellion."

3. **Select GPT Model**: Choose the GPT model you prefer. The options include:
   - `gpt-3.5-turbo`
   - `gpt-3`
   - `text-davinci-003`
   - `text-curie-001`
   - `text-babbage-001`
   
4. **Generate Verdict**: After entering the necessary information, click the "Generate Verdict" button to let AI Judge GPT generate the verdict.

5. **View Verdict**: The generated verdict will be displayed on the page. It includes whether the defendant is guilty or not, and if guilty, the recommended legal punishment.

## Example Input
**Case Description**: "A political leader allegedly incited rebellion and tried to overthrow the government."

**GPT Model**: `gpt-3.5-turbo`

**API Key**: Your OpenAI API key.

**Result**: The application will generate a verdict with the judge's decision.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Thanks to [OpenAI](https://openai.com/) for providing the GPT models.
- This project was created as part of an AI-based legal simulation.

## Contact
For any inquiries or contributions, feel free to open an issue or contact me directly.

**GitHub Username**: [hwkims](https://github.com/hwkims)
```

### 주요 변경 사항:
1. **English Demo Link**:
   - The live demo link in English is added as **[GitHub Pages](https://hwkims.github.io/AI-Judge/)** so users can try the application.

2. **General Content**:
   - The rest of the content is the same as the Korean version, explaining how to use the application, from entering the OpenAI API key to generating the verdict with the selected GPT model.

### 요약:
이 README.md 파일은 영어 사용자들이 AI Judge GPT를 쉽게 이해하고 사용하도록 돕습니다. **GitHub Pages**에서 제공하는 영어 버전 데모 링크를 통해 사용자는 애플리케이션이 어떻게 작동하는지 직접 확인할 수 있습니다.
