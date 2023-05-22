# CSE 15L Lab 4 Report 
# Haotong Wu 
# May 21, 2023
## Step 1 - Log into ieng6 account
1. Open the Visual Studio Code Application
<img width="769" alt="osc" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/ae7fa5ec-646e-450b-9293-c2ebf0a4bf3a">

2. CLick Terminal and Open the terminal window
<img width="689" alt="ternimal" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/efe3f93b-162b-44f7-bf5f-7695b25a7f49">

3. Login in to the ieng6 account, typying ssh cs15lsp23jf@ieng6.ucsd.edu and then the passward
<img width="577" alt="login" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/bf48cc89-137d-4352-be73-08b3be8be7eb">

## Step 2 - Clone your fork of the repository from your Github account
1. Follow the instrcution to clone the [link](https://github.com/ucsd-cse15l-w23/lab7) here
<img width="909" alt="lab" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/4366548f-a430-40ad-9423-64d0f3fe40ff">

2. Click the code button in green and click open with Github desktop
<img width="329" alt="desktop" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/7c86cf9a-2890-4b56-bd30-860326ccf457">

3. Click clone to clone button in blue
<img width="601" alt="clone" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/9c93d73b-7f8f-4fe5-9851-6292fab69b76">

4. Click the white button showing open with visual studio code
<img width="485" alt="open" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/b33ad0ef-e425-4ae8-9740-964c69b77065">

## Step 3 - Run the tests, demonstrating that they fail
1. After open the files through Visual Studio Code you should see something like this
<img width="1128" alt="col" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/65b6a7b8-877f-4fde-962a-403bef49ef58">

2. Open the Terminal and run the bash test.sh and we see the test failed
<img width="589" alt="Screen Shot 2023-05-22 at 12 24 17 PM" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/7da50e0a-6b29-4207-b818-277e61e3affe">
<img width="580" alt="Screen Shot 2023-05-22 at 12 25 19 PM" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/970f5706-1b88-49f6-b561-5753d5ca04f1">

## Step 4 - Edit the code file ListExamples.java to fix the failing test (as a reminder, the error in the code is just that index1 is used instead of index2 in the final loop in merge)
1. We open the vim and using the method in vim to change the index1 to index2 in the final loop in merge
2. We press the key <j> 42 times to move to the line 43
3. Press the key <i> 12 times to move to the right 
4. Press the key <r> to change the character 1 to 2
5. Press the key <ESC> to exit vim mode

## Step 5 - Run the tests, demonstrating that they now succeed
1. Rerun the test by bash test.sh and we see no errors and OK
<img width="533" alt="Screen Shot 2023-05-22 at 12 40 55 PM" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/3ce63a31-c50a-44d2-a232-5e98a2b19626">

  
## Step 6 - Commit and push the resulting change to your Github account



