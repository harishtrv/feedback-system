# Feedback-system

## Technologies:
	-React TypeScript
	 reason: to learn better, it has good options
	-Java quarkus
	 reason: to learn, java faster than python

## Options:
	-allows to login with user and PW
  
	/
		-dashBord to show user created feedbacks with response report(goto /report/#ID) and list of pending feedback requests from others(goto /give-feedback/#id)
		-topbar - logout, "create" feedback questions and options (goto /create-feedback)
		-profile - goto /profile
    
	/create-feedback
		-collect all questions and options
		-ask analytical words with examples to analyse (+ve or -ve) the commeneted feed backs.
		-after submit ask which are the users to be requested for this feedback.
		-deadline time.
		-show the auto generated ID.
    
	/give-feedback/#id
		-show the questions and options in the end input for comment
		-on submit update the analytics in the feedback requester board.
    
	/report
		-this should show the question and options with %of people selected those options for the question
		-for input field comment the report of feedback points must be given(+ve fb +5 point and -ve feedback -2 point)
	
		
	
	
