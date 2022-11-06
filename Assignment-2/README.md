1. Create a file like nano file1.txt
----
#cmd:

      echo "this is a file" > file1.txt
----

2. Now we will copy date from file1 to new file2
o cp file1.txt file2.txt
o Then see the output of file2.txt, cat file2.txt

<img width="736" alt="image" src="https://user-images.githubusercontent.com/116376587/200175326-b3161388-9d56-49a7-b9a4-34dcff650561.png">

----
#cmd: 
    
     cp file1.txt file2.txt 
     cat file2.txt 
----

3. Now we will move the file2.txt to new folder /home
<img width="618" alt="image" src="https://user-images.githubusercontent.com/116376587/200175362-2e0bef96-be09-4a5f-86c7-d73805d5dfef.png">
<img width="618" alt="image" src="https://user-images.githubusercontent.com/116376587/200175403-bc624aca-d2b5-43df-b5a9-70cc4ce59e1f.png">

----
#cmd: 

     cp file2.txt home 
     ls -lrt home/file2.txt 
----

4. Then we create a new file3.txt and file4.txt in home directory and add
content in it.
o Now do echo “Hello I am newline” > file3.txt and provide the
output of file3.txt
o Now do echo “Hello I am newline” >> file4.txt and provide the
output of file4.txt
o Tell the different between both step you follow and the reason
behind it

<img width="775" alt="image" src="https://user-images.githubusercontent.com/116376587/200175448-df084142-842c-4f59-930e-26c92b9c22ec.png">


#Ans: 
  1. when we use echo "some content with > " > file.txt, then it means that it will remove existing content and put the new content that we are echoing.
  2. when we use echo "some content with >>" >> file.txt, then it means that it will append the content to the existing content, unlike (>) which removes previous content.


-----
#cmd: 

     echo “Hello I am newline in file3” > file3.txt
     echo “Hello I am newline in file4” >> file4.txt
     
      cat file3.txt file4.txt 
     
“Hello I am newline in file3”
“Hello I am newline in file4”
----

5. For remove a file or directory you can use the below two commands

<img width="775" alt="image" src="https://user-images.githubusercontent.com/116376587/200175499-b0f6a9b7-9cf2-40ec-bf8e-c36203ae5514.png">

----
#cmd

    rm file1.txt
----
