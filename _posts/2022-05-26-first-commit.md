<!DOCTYPE html>
<html xmlns:th="http://www.thymeleaf.org">
<head>
	<meta charset="UTF-8">
	<title>index</title>
	<!-- 
		날짜 : 2022/04/13
		이름 : 강태호
		내용 : Ch09.Spring REST API
		
		REST API(RESTful)
		 - URI를 설계할 때 기존 GET, POST 이외에 PUT, DELETE를 추가해서 설계해서 요청하는 방식
		 - A태그는 GET만 지원하고, Form은 GET/POST만 지원하기 때문에 REST API는 AJAX로 요청한다.
		 - REST API의 응답결과는 화면(Html)이 아닌 데이터(Json, xml 등)이다.
	 -->
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
	<script th:src="@{/js/user.js}"></script>
	<script th:src="@{/js/member.js}"></script>
	<script th:src="@{/js/employee.js}"></script>
	<script th:src="@{/js/customer.js}"></script>
</head>
<body>
	<h3>Spring REST API 실습</h3>
	
	<h4>User</h4>
	<button class="user_List">User 목록</button>
	<button class="user_Register">User 등록</button>
	<button class="user_Modify">User 수정</button>
	<button class="user_Delete">User 삭제</button><br><br>
	
	<h4>Member</h4>
	<button class="member_List">Member 목록</button>
	<button class="member_Register">Member 등록</button>
	<button class="member_Modify">Member 수정</button>
	<button class="member_Delete">Member 삭제</button><br><br>
	
	<h4>Employee</h4>
	<button class="employee_List">employee 목록</button>
	<button class="employee_Register">employee 등록</button>
	<button class="employee_Modify">employee 수정</button>
	<button class="employee_Delete">employee 삭제</button><br><br>
	
	<h4>Customer</h4>
	<button class="customer_List">customer 목록</button>
	<button class="customer_Register">customer 등록</button>
	<button class="customer_Modify">customer 수정</button>
	<button class="customer_Delete">customer 삭제</button><br><br>
	
</body>
</html>
