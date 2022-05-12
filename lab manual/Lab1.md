## Objective:
*   To prepared an environment to run and compile the project.
*   Create a super user and users, as well as run the server.
*  To test CRUD operations and add components.
## Introduction:
* For this lab, we implement a variety of frameworks and platforms. The IDE was Visual Studio Code, and the framework was Python/Django. An e-commerce website is one that allows users and sellers to buy and sell things over the internet. It is one of the most effective current company models. E-commerce platforms make purchasing products and services easier. For this lab report, we will create an e-commerce website.
This lab also uses Git for source control. We may also utilize Github Desktop to commit and push our work to a GitHub repository. When that repository is made public, everyone can examine it.
## Procedure:
1.  We Download Python3, pip or pip3, Sqlite, DBeaver community, Django, VS code, Github account.
2.  Open command use to check whether python is install or not.
Syntax:
 python3 –version
3.  Initialize Django project to create the user 
Syntax:
django-admin startproject ecommerce_ashna
cd ecommerce_ashna
4.  Migrating and creating users
Syntax:
 ecommerce_ashna
python manage.py migrate
in this process we got link for server for 127.0.0.1:8000
5.  Verify the admin side using 127.0.0.1:8000\admin
Syntax:
python manage.py runserver
6.  Database verification and CRUD operations:
Syntax:
python manage.py startapp product_module
python manage.py runserver
7.  Source Control
Lastly, for source control, we utilized Git. We built a repository called ecommerce ashna and a markdown file called "lab1.md" that contains this document. The code and folder were then committed and published to the repository. The repository may now be found at: https://github.com/anhsaa/ecommerce_lab1
36
## Output:
* Installation of python| pip

![alt text](https://scontent.fktm8-1.fna.fbcdn.net/v/t1.15752-9/278162363_535159071348207_4631905168955827836_n.png?_nc_cat=107&ccb=1-6&_nc_sid=ae9488&_nc_ohc=yVxHf-Jgq8IAX-4bR_m&_nc_ht=scontent.fktm8-1.fna&oh=03_AVJh5Rac7ep52PMV0rYftEwHz-YYWPPDdPCyzeWP111euA&oe=62A15D25)

* Creation of project folder

![alt text](https://scontent.xx.fbcdn.net/v/t1.15752-9/280298287_419373520010677_8787542285354514019_n.png?stp=dst-png_p206x206&_nc_cat=107&ccb=1-6&_nc_sid=aee45a&_nc_ohc=SkgQBSqW_cAAX9_LH57&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AVL1eSKu4GiGTpA-5uEuVzqo-omAVMRlWYeW5ptHnkBz9g&oe=62A30D86)

* Migration and creating super user:

 ![alt text](https://scontent.xx.fbcdn.net/v/t1.15752-9/280110007_520999829525030_6320577654250451081_n.png?stp=dst-png_p206x206&_nc_cat=110&ccb=1-6&_nc_sid=aee45a&_nc_ohc=0TUqKDyFRY8AX_aw6T5&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AVIOpnwiu1OguhQ-SzJI-j1k1fM5IQF6eIUX4v5uhdL1ZA&oe=62A25061)

* Running server

![alt text](https://scontent.xx.fbcdn.net/v/t1.15752-9/280326100_374482437946718_5000888598667940158_n.png?stp=dst-png_p206x206&_nc_cat=103&ccb=1-6&_nc_sid=aee45a&_nc_ohc=J_7vBdcCeOkAX-VdWNa&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AVJjBmEr1z07s3ZAWPRF0zfUMZ9ZNFKQ8zp4sVKG-qml3w&oe=62A17CB4)
 

* Logging In

![alt text](https://scontent.xx.fbcdn.net/v/t1.15752-9/280100316_1003713720281266_8116799199405200024_n.png?stp=dst-png_p206x206&_nc_cat=110&ccb=1-6&_nc_sid=aee45a&_nc_ohc=UoCtO5jCiLMAX_2OAib&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AVLwHUCcfgLp79P9plR7XghJsMi_Jr6nx9YGulWPwWde1Q&oe=62A38007)
 
* CRUD operation

![alt text](https://scontent.xx.fbcdn.net/v/t1.15752-9/280132448_703991261024894_619684829338131239_n.png?stp=dst-png_p206x206&_nc_cat=111&ccb=1-6&_nc_sid=aee45a&_nc_ohc=67OCJ2c5D5AAX9IRd4w&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AVJWXh-08h7ZYqAuDWqiG92pYTiQB4otw0h2rf-TAvFEgw&oe=62A1DD2E)
 

## Conclusion:
In this lab we setup allowed us in quickly creating scenarios and setting up. Then we knew how to create a Django project. It was also learned how to operate the server. On the server, we knew how to do CRUD operations. Finally, we learned more about Git and Github for source control. Our code was easily available when we created a Github repository and shared it.



