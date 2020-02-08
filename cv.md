# **Brief Resume**

**1. First Name, Last Name:** *Alexandr Nemogai*

**2. Contact info:** *+375-29-324-26-83 Vel, Viber, Telegram; sanjamogai -> Instagram*

**3. Summary:** *My goal is to become a programmer. Good training and a friendly atmosphere are important to me! I want  to get knowledge and pass your tests.*

**4. Skills:** *a little C, C++, C#, assember from the university and a little JS from the courses.*

**5. Code examples:** *some task a year ago*


    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8">
        <title>HomeWork3</title>
    </head>
    <body>
        <script type="text/javascript">

            function task1(){

                var loginAdmin = 'Админ',
                    passw0rdAdmin = 'Черный властелин',
                    someLogin,
                    someAttemptPassw0rd;

                someLogin = prompt('Enter login','дай угадаю, Вася?');

                if( someLogin === loginAdmin){

                    someAttemptPassw0rd = prompt('Enter passw0rd, pozhaluista','Ломай, Уася!');

                    if(someAttemptPassw0rd === passw0rdAdmin){
                        alert('Добро пожаловаться!');
                        } else if(someAttemptPassw0rd != passw0rdAdmin && someAttemptPassw0rd != null){
                        alert('Слущай, еще пробуй потом, Уася!');
                        } else {
                            alert('Уходи, не плачь=)');
                        }

                } else if(someLogin !=loginAdmin && someLogin != null){
                alert('Ты кто такой? Давай, до свиданья, слушай!');
                } else {
                    alert('Уходи, не плачь=)');
                }
            }

            function task2(){

                var message,
                    login = prompt('Enter login','(^_^)');

                    login === 'Вася' ? message = 'Привет' :
                    login === 'Директор' ? message = 'Здравствуйте' :
                    login === '' ? message = 'Нет логина' :
                    message = '';

                alert(message);
            }

            function task3(){
                var evenNumber = 'even numbers from two to ten:';
                for(var i  = 0; i <= 10; i++){
                    if(i%2 == 0 && i != 0)
                        evenNumber += i + ' ';
                }
                alert(evenNumber);
            }

            function task4(){

                var onlyNumbers = [],
                    someWritingPeople,fff;

                for(i = 0 ;; i++){
                    someWritingPeople = prompt('Введите число','Пожалуйста,число, не ломайте программу!');
                    if(someWritingPeople === null || someWritingPeople === '' || someWritingPeople != +someWritingPeople){
                        alert('Раз не хотите вводить числа, я вынужден сказать вам до свиданья!');
                        break;
                    } else {
                        onlyNumbers [i] = someWritingPeople;
                    }
                }

                onlyNumbers.forEach(function(item,i,onlyNumbers){
                fff+= item;
                });
                alert(fff);
            }

            var menu = +prompt('Выберите 1 из 4 омашних заданий!','-1-2-3-4-чо');
            switch(menu){
                case 1: task1(); break;
                case 2: task2(); break;
                case 3: task3(); break;
                case 4: task4(); break;
                default: alert('Неправильный выбор, разберитесь в себе=)');
            }

        </script>
    </body>
    </html>


**6. Experiense:** *tasks at university and courses*

**7. Education:** *BSUIR, TechMeSkills, HTMLacademy*

**8. English:** *At school. I have an elementary level, but I learn English in courses.*

***