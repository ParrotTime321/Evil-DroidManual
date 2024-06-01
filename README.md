# Evil-DroidManual

              .           .                                                                                                                                          
              M.          .M                                                                                                                                         
               MMMMMMMMMMM.                                                                                                                                          
            .MMM\MMMMMMM/MMM.                                                                                                                                        
           .MMM.7MMMMMMM.7MMM.                                                                                                                                       
          .MMMMMMMMMMMMMMMMMMM                                                                                                                                       
          MMMMMMM.......MMMMMMM                                                                                                                                      
          MMMMMMMMMMMMMMMMMMMMM                                                                                                                                      
     MMMM MMMMMMMMMMMMMMMMMMMMM MMMM                                                                                                                                 
    dMMMM.MMMMMMMMMMMMMMMMMMMMM.MMMMD                                                                                                                                
    dMMMM.MMMMMMMMMMMMMMMMMMMMM.MMMMD                                                                                                                                
    dMMMM.MMMMMMMMMMMMMMMMMMMMM.MMMMD                                                                                                                                
    dMMMM.MMMMMMMMMMMMMMMMMMMMM.MMMMD                                                                                                                                
    dMMMM.MMMMMMMMMMMMMMMMMMMMM.MMMMD                                                                                                                                
    dMMMM.MMMMMMMMMMMMMMMMMMMMM.MMMMD                                                                                                                                
    dMMMM.MMMMMMMMMMMMMMMMMMMMM.MMMMD                                                                                                                                
     MMM8 MMMMMMMMMMMMMMMMMMMMM 8MMM                                                                                                                                 
          MMMMMMMMMMMMMMMMMMMMM                                                                                                                                      
          MMMMMMMMMMMMMMMMMMMMM                                                                                                                                      
              MMMMM   MMMMM  v0.3                                                                                                                                    
              MMMMM   MMMMM                                                                                                                                          
              MMMMM   MMMMM                                                                                                                                          
              MMMMM   MMMMM                                                                                                                                          
              .MMM.   .MMM.                                                                                                                                          
      Mascerano Bachir - Dev-labs                                                                                                                                    
                                                                                                                                                                     
╔──────────────────────────────────────────────╗                                                                                                                     
|          Evil-Droid Framework v0.3           |                                                                                                                     
|      Hack & Remote android plateform         |                                                                                                                     
┖──────────────────────────────────────────────┙                                                                                                                     
[1] APK MSF                           - Створення шкідливого додатку, який використовує Metasploit для атаки на Android-пристрій.
[2] BACKDOOR APK ORIGINAL (OLD)       - Створення додатку з прихованим доступом для віддаленого керування пристроєм.
[3] BACKDOOR APK ORIGINAL (NEW)       - Те ж саме, але з оновленими можливостями.
[4] BYPASS AV APK (ICON CHANGE)       - Створення додатку, який міняє іконку для ухилення від деяких антивірусів.
[5] START LISTENER                    - Початок прослуховування порта який відкривається коли "жертва" запускає вірус, тобто ця опція використовується лише тоді коли уже є відкритий порт
[c] CLEAN                             - Видалення тимчасових файлів і данних
[q] QUIT                              - Вихід

============================================================================================
Далі наприклад виберемо пункт 3
Після його вибору у нас попросить поставити ip адресс сервера який буде займатись прослуховуванням порта, тобто вашої віртуальної машини, в більшості випадків Evil-Droid сам вписує потрібний, але на всякий випадок краще перевірити чи співпадають ip адресси
Настпне що потрібно буде ввести це порт, головне вибирати той який буде пустим наприклад 7777
Далі вводимо назву яку хочемо мати у файла з вірусом
Після введення назви нас просять вибрати яким способом будем приєднуватись до "жертви" виберем reverse_tcp
Далі йде вибір файлу в який буде інсталюватись вірус, в багатьох випадках під час тестування на пустий .apk файл Evil-Droid не ставив вірус, тому краще вибрати існуючий apk
Після компіляції шкідливого файлу йде вибір інструменту для прийому з'єднання виберем наприклад Multi-Handler
Далі все можна глянути в мануалі по Metasploit ось наприклад офіційний мануал - Metasploit Documentation: https://docs.metasploit.com/
