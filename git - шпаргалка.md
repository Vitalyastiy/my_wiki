### Содержание  

crontab - e - открыть крон
crontab - r - дропнуть крон
git rev-parse --show-toplevel - показать где я 

scp /c/Users/flerinvs/Desktop/pass.json flerinvs@webapp-01-prd:/home/flerinvs/lab/ - копировать файл

scp /c/Users/flerinvs/Desktop/Отчет_ЭлРег2.0_Райффайзен_банк.xlsx flerinvs@webapp-01-prd:/home/flerinvs/lab/ - копировать файл


$ ssh flerinvs@webapp-01-prd "rm 2024-05-05_report_podft.txt" - удаление файла через SSH

ssh flerinvs@webapp-01-prd "find -name '*.txt' -exec rm {} \;"

vim /путь/к/файлу.json - открыть и редактировать json (:w - сохранить, :q - выйти)

rm * 2024 * -- удалить все где в названии есть 2024
rm* - удалить все
rm -i * 2024* - запросить разрешение для каждого файла 


scp /c/Users/flerinvs/Desktop/Миграция_компании_ВТБ.xlsx flerinvs@webapp-01-prd:/home/flerinvs/lab/

scp /c/Users/flerinvs/Desktop/Миграция_моно_заявки_ВТБ.xlsx flerinvs@webapp-01-prd:/home/flerinvs/lab/

scp /c/Users/flerinvs/Desktop/Свод_по_мульти_ВТБ_ФЛ_ЧМ.xlsx flerinvs@webapp-01-prd:/home/flerinvs/lab/

scp /c/Users/flerinvs/Desktop/Свод_по_мульти_ВТБ_ЮЛ.xlsx flerinvs@webapp-01-prd:/home/flerinvs/lab/



scp flerinvs@webapp-01-prd:/home/flerinvs/2024-05-08_report_podft.txt "C:\Users\flerinvs\Desktop" - Скачать в обратную сторону


less pass.json -- как открыть файл джейсон на серве
