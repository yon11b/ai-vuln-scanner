## 실행 명령어

진단코드만: `python3 auto-scanner/scanner.py --target [대상URL]`<br>
대시보드:
- `pip3 install -r moduleproj2/requirements.txt`
- `streamlit moduleproj2/run app.py`

## 개요

AI 기반 웹사이트 취약점 진단 툴입니다.

취약한 웹사이트<br>
<img width="811" height="553" alt="image" src="https://github.com/user-attachments/assets/bbd31e17-c298-4c0a-8180-7024ae0c49d5" />


<img width="579" height="832" alt="image" src="https://github.com/user-attachments/assets/c8329d5c-eb0e-4794-8566-72d8e3b3f449" />


대시보드<br>
<p align="center">
  <img width="600" alt="image"src="https://github.com/user-attachments/assets/ee6cb22e-30c0-45c8-815c-9aaf6b1b3c00" />
</p>

<p align="center">
  <img width="600" alt="image" src="https://github.com/user-attachments/assets/d64c93bc-f52d-416f-b5c9-223e3ab8e44c" />
</p>


## 구조도

취약한 웹서버 환경<br>
<img width="60%" alt="image" src="https://github.com/user-attachments/assets/d5c1f5d2-fdf3-43b8-b326-e685d469f3aa" />

취약점 진단 시스템 구조도<br>
<img width="60%" alt="image" src="https://github.com/user-attachments/assets/7f993b3d-8996-40ea-b62e-24f1782143dc" />


## 협업 툴

Notion [[링크]](https://www.notion.so/4-2-360b3aca18a480aa826ddada7d8fa87b?source=copy_link)<br>
<img width="60%" alt="image" src="https://github.com/user-attachments/assets/12d3b441-3e91-47b3-a8e1-2efd8da93ee3" />


## 기술스택

- 취약점 진단코드: Python
- LLM: GPT-5.5 (via OpenAI API)
- DB: mariaDB
- Front: streamlit
- Server: NGINX
- WAS: Tomcat
- 취약한 웹사이트: JSP
- 클라우드 서버: EC2 t3.medium

## 팀 정보

<br>
<table align="center" width="700" border="1" cellspacing="0" cellpadding="10" style="border-collapse: collapse; text-align: center;">
  <thead style="background-color: #f2f2f2;">
    <tr>
      <th width="150">성명</th>
      <th width="550">역할</th>
    </tr> 
  </thead>
  <tbody>
    <tr>
      <td>김세권</td>
      <td>
        - GPT 기반 취약점 자동진단 툴 개발<br>
        - 수동진단 시트 작성
      </td>
    </tr>
    <tr>
      <td>백하연</td>
      <td>        
        - 시그니처 기반 취약점 자동진단 툴 개발<br>
        - 취약한 웹 서버 시큐어 코딩 개발<br>
        - 협업 툴 관리
      </td>
    </tr>
    <tr>
      <td>서우혁</td>
      <td>
        - 취약점 대시보드 만들기<br>
        - 백엔드 연동 및 시각화
      </td>
    </tr>
    <tr>
      <td>이채윤</td>
      <td>
        - 취약점 대시보드 만들기<br>
        - 백엔드 연동 및 시각화
      </td>
    </tr>
    <tr>
      <td>최준희</td>
      <td>
        - 취약점 대시보드 만들기<br>
        - 백엔드 연동 및 시각과
      </td>
    </tr>
    <tr>
      <td>한병헌</td>
      <td>
        - 취약한 웹 서버 개발(Nginx, Tomcat, MariaDB)<br>
        - AWS 환경 관리
      </td>
    </tr>    
  </tbody>
</table>
<br>

## 결과 화면

#### 1. URL 기반 실시간 자동진단

<p align="center">
  <img width="600" alt="image" src="https://github.com/user-attachments/assets/fcc31175-66a8-4746-b95c-8e9ce1c8ccdf" />
</p>

<p align="center">
  <img width="600" alt="image" src="https://github.com/user-attachments/assets/13e08577-7f53-4727-a78d-ad63a08e0092" />
</p>

<p align="center">
  <img width="600" alt="image" src="https://github.com/user-attachments/assets/9cd19ccc-5701-43b5-bb26-54a7fdf09d46" />
</p>

<p align="center">
  <img width="600" alt="image" src="https://github.com/user-attachments/assets/6d652f4c-7d17-4cc9-9a6e-957900d6fdab" />
</p>

---

#### 2. 자동진단 수동진단 비교

<p align="center">
  <img width="650" alt="image"  src="https://github.com/user-attachments/assets/5ece4bea-1b27-4ede-bbcf-02fc650f3d21" />
" />
</p>

<p align="center">
  <img width="650" alt="image" src="https://github.com/user-attachments/assets/8395f9a6-5e5f-40da-aa87-c198b6fb855d" />
" />
</p>

<p align="center">
  <img width="650" alt="image" src="https://github.com/user-attachments/assets/689e5613-1d9a-4bad-8bec-ecbd90533c9b" />
" />
</p>

<p align="center">
  <img width="650" alt="image" src="https://github.com/user-attachments/assets/0a1e14de-cbe1-43f0-a9c3-906c7894b760" />
" />
</p>

<p align="center">
  <img width="650" alt="image" src="https://github.com/user-attachments/assets/a8b80cb2-96b1-4c8b-b048-1369235b2861" />
" />
</p>
---

#### 3. 취약한 웹사이트
<img width="647" height="644" alt="image" src="https://github.com/user-attachments/assets/53e51a76-d0d8-4e41-9dc6-d12088908407" />
<img width="592" height="630" alt="image" src="https://github.com/user-attachments/assets/7149ee43-0634-4cac-bb90-04911e61d415" />
<img width="605" height="667" alt="image" src="https://github.com/user-attachments/assets/03fa9a78-6e8f-476d-8c18-75e881273dd3" />
<img width="619" height="508" alt="image" src="https://github.com/user-attachments/assets/5c9fb4ff-2088-40a3-87af-02e97899f22d" />
