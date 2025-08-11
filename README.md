# localAdmin

# 주민센터 관리자 대시보드 스프링 프로젝트 (Java + Spring Legacy + Oracle)




관리자를 위한 민원/게시물/회원/댓글 관리 백오피스입니다.  
스프링 **Legacy MVC** 구조(Controller–Service–Mapper–View) 위에 **Spring Security** 인증/인가,
**MyBatis** + **Oracle** 연동, **JSP/JSTL + Bootstrap** UI, **jQuery/Ajax** 기반의 비동기 댓글(Reply) 모듈, 
페이징/검색/모달 등을 구현했습니다.

---

## 사용 기술
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=fff"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=fff"/> 
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=fff"/> 
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=fff"/> 
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=fff"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=fff"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=Oracle&logoColor=4479A1"/> 
  <img src="https://img.shields.io/badge/JAVA-8F0000?style=flat-square&logo=Java&logoColor=4479A1"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Notion-ffffff?style=flat-square&logo=Notion&logoColor=black"/> 
  <img src="https://img.shields.io/badge/GitHub-gray?style=flat-square&logo=GitHub&logoColor=black"/> 
  <img src="https://img.shields.io/badge/Git-blue?style=flat-square&logo=Git&logoColor=F05032"/> 
  <img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=#007ACC"/> 
  <img src="https://img.shields.io/badge/Eclipse IDE-2C2255?style=flat-square&logo=eclipseide&logoColor=#fff"/> 
</p>

---

## 핵심 기능
- 🔐 **인증/인가**: Spring Security (로그인, 권한별 접근 제어)
- 📄 **게시물/민원 관리**: CRUD, 카테고리/상태, 다중 조건 검색, 페이지네이션
- 💬 **댓글(Reply) REST 모듈**: jQuery/Ajax로 비동기 등록/수정/삭제/조회
- 👥 **회원 관리**: 권한(Role) 기반, 활성/비활성, 최근 활동 로그
- 📊 **대시보드**: 통계 카드/차트(일간/주간/카테고리 분포)
- 🧰 **운영 편의**: 모달 기반 폼, 일괄 작업, 서버 로그(Log4j), 예외 처리 페이지

---

## 기획서보러가기
<a href="https://github.com/hyeji21/localAdmin/issues/1#issue-3308284286">
  <img width="1114" height="625" alt="Image" src="https://github.com/hyeji21/localAdmin/issues/1#issuecomment-3173135867"/>
</a>
---

## 워크플로우

