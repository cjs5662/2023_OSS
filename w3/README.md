## 3주차 git

### 이미지

![cm_2_3](https://user-images.githubusercontent.com/127291602/227786718-b9886113-28b0-411e-aa78-f76f2de8dc3c.jpg)


#### 링크

[LMS](https://lms.kau.ac.kr/login.php)

##### Progit 링크

[ProGit](https://git-scm.com/book/en/v2)

##### 주요 Git명령어


##### 2주차 숙제 코드블록
#!/usr/bin/env bash   
echo "----------"   
echo "name :"   
echo "OOO"   
echo   
   
echo "----------"   
echo "student id :"    
echo "0000000000"   
    
file path= 'find /home/kau2/ -name w2_homework.txt 2> /dev/null'    
echo "----------"    
echo    
echo "file path :"    
$file_path    
echo    
    
line_num= 'wc -1 $file_path | cut -c 1 -'    
echo "----------"    
echo "line number :"    
echo $line_num    
echo    
    
echo "----------"    
echo "lask line :"    
tail -n 1 $file_path
