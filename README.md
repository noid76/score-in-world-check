# score-in-world-check
check the exam you ever been in the world

# Country Final Exam
print('Please select country')
country = input("'malaysia', 'amerika', 'indonesia', 'china', 'mongolia': ").lower()  # .lower() untuk mengurangkan masalah besar kecil huruf

# Mengambil markah peperiksaan dan menukarkannya ke integer
EXAM_SCORE = int(input("Enter your exam score: "))

# Periksa negara dan markah
if country == 'malaysia' and EXAM_SCORE >= 50:
    print("You passed the exam in Malaysia!")
elif country == 'amerika' and EXAM_SCORE >= 60:
    print("You passed the exam in Amerika!")
elif country == 'indonesia' and EXAM_SCORE >= 55:
    print("You passed the exam in Indonesia!")
elif country == 'china' and EXAM_SCORE >= 100:
    print("You passed the exam in China!")
elif country == 'mongolia' and EXAM_SCORE >= 80:
    print("You passed the exam in Mongolia!")
else:
    print("You failed the exam or country not listed.")



https://www.programiz.com/online-compiler/9jRhtTzbJvMww


