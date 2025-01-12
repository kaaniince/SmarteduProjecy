# SmarteduProject

Smartedu bir eğitim platformudur. İçerisinde öğrenci, öğretmen ve adminleri barındırır. Register ve Login ile sisteme giriş yapılır. Register olmadan yapılan login'ler geçersiz olacaktır. Admin ise admin panelden giriş yapmaktadır. Öğretmenler kendilerine ait kurs oluşturabilirler. Oluşturdukları kursu silebilir veya güncelleyebilirler. Platforma kayıtlı öğrenciler ise bu kurslara enroll veya release olabilirler. Kursların bulunduğu bölümde kategorilere göre filtreleme ve arama işlemleri gerçekleştirilebilir. MVC tabanlı bir yaklaşım yakalanmıştır.

## Used Technologies

```
bcrypt
connect-flash
connect-mongo
dotenv
ejs
express
express-session
express-validator
method-override
mongoose
slugify
```

![PROJECT](/images/landing-page.png)

![PROJECT](/images/landing-page2.png)

MongoDB'den sisteme kayıtlı öğrenci, öğretmen, admin ve kurslara erişim sağlanmıştır.

![PROJECT](/images/login.png)

![PROJECT](/images/teacher.png)

![PROJECT](/images/teacher_course.png)

![PROJECT](/images/courses.png)

![PROJECT](/images/student.png)

## Installation

Öncelikle projeyi clonelayın.

```
git clone https://github.com/kaaniince/SmarteduProject.git
```

## Usage

Projeyi cloneladıktan sonra Visual Studio Code programında açınız.

Linux için:

```
cd SmarteduProject
code .
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
