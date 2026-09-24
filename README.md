
Request body: { topic, name, email, dept, score, answers }
POST /check-quiz-attempt

Check if a user has attempted a specific quiz.
Request body: { email, topic }
POST /check-teacher-marks

Get marks for a specific quiz topic.
Request body: { quizTopic }
POST /check-student-marks

Get marks for a specific student.
Request body: { email }
