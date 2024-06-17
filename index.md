
# This is an `<h1>` header
### This is an `<h3>` header 
Below is an image of a donkey

![Image of a donkey](https://th.bing.com/th/id/OIP.MWxF-GHlwBAk8vukyDkfoQHaHl?rs=1&pid=ImgDetMain)

Below is code for generating a Collatz sequence

    print('Enter number:')
    number = int(input())

    def collatz(number):

        if number % 2 == 0:
            return number//2

        elif number % 2 == 1:
            return number*3 + 1



    sequence = [number]
   
    while number != 1:


    number = collatz(number)
    sequence += [number]
    

    print(sequence)
    print('This sequence has ' + str(len(sequence)-1) + ' steps')
