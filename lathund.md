# Lathund för Git

## Fork
Fork skapar en personlig kopia av någon annans projekt som man kan redigera och mergea med orginalrepot. Man gör det med hjälp av en knapp i webbläsaren.

## Clone
Den laddar ner en klon av projektet man gafflat så att man kan redigera den och sedan kan pusha upp den.
´´´
git clone https://github.com/USERNAME/REPO
´´´

## Push
Push laddar upp alla ändringar man gjort lokalt så att alla kan komma åt dom.
´´´
git push -u origin master
´´´

## Add
Add lägger till nya ändringar som man sedan kan committa.
´´´
git add <Filename>
´´´

## Commit
Sparar indexet av alla ändringar som är tillagda med add.
´´´
git commit -m "message"
´´´ 

## Origin
Origin är smeknamnet som git har lokalt på repot online.

## Pull Request
En pull request är när man ber skaparen av repot som man klonade med fork att få sätta ihop det med orginal repot efter att man har ändrat på filerna.