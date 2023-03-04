# magic_8_ball
The Magic 8 Ball is a plastic sphere, made to look like an oversized eight ball , that is used for fortune-telling or seeking advice.


    import random
    def get_answer(answer_number):
        if answer_number == 1:
            return 'It is certain'
        elif answer_number == 2:
            return 'It is a matter of time'
        elif answer_number == 3:
            return 'Yes'
        elif answer_number == 4:
            return 'Very doubtful'
        elif answer_number == 5:
            return 'Ask again later'
        elif answer_number == 6:
            return 'Concetrate and ask again'
        elif answer_number == 7:
            return 'My reply is NO'
        elif answer_number == 8:
            return 'Outlook not so good'
    r = random.randint(1,8)
    fortune = get_answer(r)
    print(fortune)

