# Assessment Feedback System (AFS)
A Java Swing-based desktop application developed for managing academic assessments, grading, feedback, and performance monitoring through role-based access control.
Features


Role-based dashboards for:

	Admin Staff
	Academic Leaders
	Lecturers
	Students

Assessment creation and management:

	Marks and grading system
	Lecturer feedback system
	Student results and module summaries
	Report generation and analysis
	Class and module management
	MD5 hashed password authentication

Technologies Used:

	Java
	Java Swing
	Object-Oriented Programming (OOP)
	Text-file storage

System Roles:

	Admin Staff
		Manage users
		Manage classes and modules
		Configure grading system

	Academic Leader
		Manage modules
		Assign lecturers
		Generate reports and module summaries

	Lecturer
		Create assessments
		Enter marks
		Provide feedback

	Student
		Register classes
		View results and feedback
		Submit lecturer comments


Project Structure

	GUI/ – User interface
	Users/ – User role classes
	Entity/ – Core system entities
	IOManage/ – File handling and data management
	data/ – Text-file database storage

Security

	Passwords stored using MD5 hashing
	Protected root superadmin account

Limitations

	Uses MD5 hashing (not fully secure)
	Text-file storage instead of database
	No audit trail or backup mechanism


Authors

	Group 6 – APD2F2511CS(CYB)
	Justin Chew Chun Yuen (Leader)
	Kelver Foo Qai Wen
	Lian Yuan Shen
