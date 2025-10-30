<div align="center">
    <img src="https://capsule-render.vercel.app/api?type=wave&color=gradient&height=180&text=김우신의%20개발%20스페이스🌟&animation=fadeIn&fontColor=000000&fontSize=50" />
</div>

## 한신대학교 재학생 김우신  

현재 한신대학교에서 **AI·SW 계열**을 전공하고 있는 학생입니다.  
꾸준히 성장하며 더 나은 **개발자 & 보안 전문가**가 되는 것이 목표입니다.  
기술을 통해 세상을 이롭게 만드는 것을 꿈꿉니다. 🚀  

---

## 🛠️ Tech Stacks

**언어 및 프레임워크**
  
![C++](https://img.shields.io/badge/C++-00599C?style=plastic&logo=C%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=plastic&logo=Python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=plastic&logo=JavaScript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=plastic&logo=React&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=plastic&logo=Node.js&logoColor=white)

**디자인 및 협업 툴**

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=plastic&logo=Figma&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=plastic&logo=GitHub&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=plastic&logo=Discord&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=plastic&logo=Notion&logoColor=white)

---

## ✨ 주요 기능 (Features)

| 기능 | 설명 |
|------|------|
| 💻 **웹 애플리케이션 개발** | React와 Node.js를 이용해 프런트엔드와 백엔드를 직접 구현 |
| 🔐 **기초 보안 로직 설계** | 사용자 입력 검증, 인증, 암호화 로직 학습 및 적용 |
| 🎨 **UI/UX 디자인** | Figma를 활용하여 직관적인 화면 구성 및 사용자 플로우 설계 |
| 🧩 **API 연동 경험** | OpenWeather, ChatGPT 등 외부 API 연동 및 데이터 시각화 실습 |
| ⚙️ **팀 협업 및 Git 관리** | GitHub를 통한 브랜치 전략, 코드 리뷰, 협업 경험 |

---

## 🧑‍💻 Contact me

<a href="https://instagram.com/woosin0218">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=plastic&logo=Instagram&logoColor=white">
</a>
<a href="mailto:mkpark7165@gmail.com">
<img src="https://img.shields.io/badge/Gmail-EA4335?style=plastic&logo=Gmail&logoColor=white">
</a>

---

## 🏅 Stats

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=default)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact)

</div>

---

## 📈 최근 활동

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

---

## ⏰ 코딩 통계

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

---

## 📘 프로젝트 개요

이 프로젝트는 **한신대학교 웹 프로그래밍 과제**로 진행되었습니다.  
요구사항 분석 → 설계 → 구현 → 테스트의 전 과정을 직접 수행하며,  
**코드의 가독성**, **유지보수성**, **UI 일관성**을 중점적으로 고려했습니다.  

**핵심 목표**
- 학습한 기술을 실제 프로젝트에 적용
- 협업 중심 개발 프로세스 이해
- 실무에서 요구되는 코드 품질 유지 능력 향상

---

## ⚙️ 실행 방법

```bash
# 1. 저장소 클론
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY

# 2. 의존성 설치
npm install

# 3. 로컬 서버 실행
npm run dev
```

> 💡 또는 Python 프로젝트인 경우:
```bash
pip install -r requirements.txt
python app.py
```

---

## ⚙️ GitHub Actions 자동 업데이트 설정

GitHub 저장소에 아래 파일을 추가하면 **최근 활동**과 **코딩 통계**가 자동 갱신됩니다.

`.github/workflows/activity.yml`
```yaml
name: Update README with recent activity

on:
  schedule:
    - cron: '0 */12 * * *'  # 12시간마다 자동 실행
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository
        uses: actions/checkout@v4

      - name: Update GitHub activity
        uses: jamesgeorge007/github-activity-readme@v0.3.0
        with:
          COMMIT_MSG: "Update README with recent GitHub activity"
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

`.github/workflows/wakatime.yml`
```yaml
name: Update WakaTime Stats

on:
  schedule:
    - cron: '0 0 * * *'  # 매일 자정
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          SHOW_UPDATED_DATE: true
          SHOW_LINES_OF_CODE: true
          SHOW_LANGUAGE: true
          SHOW_PROJECTS: true
          SHOW_OS: true
```

---

📫 **문의**  
이메일: [mkpark7165@gmail.com](mailto:mkpark7165@gmail.com)  
인스타그램: [@woosin0218](https://instagram.com/woosin0218)  

---

⭐ **감사합니다!**  
꾸준히 배우며 성장하는 개발자가 되겠습니다. 🙌
