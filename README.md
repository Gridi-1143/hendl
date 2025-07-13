<h5 align=center>
Клієнт для Linux для завантаження манг з <a href="https://hentaiukr.com/">hentaiukr.com</a> в терміналі.
</h5>

## Використання
Після встановлення напишіть ```hendl *посилання*``` або ```hendl -h``` для допомоги 

## Встановлення
```sh 
git clone "https://github.com/Gridi-1143/hendl"

sudo chmod +x hendl/hendl

sudo cp hendl/hendl /usr/local/bin
#або 
sudo cp hendl/hendl ~/.local/bin

rm -rf hendl
```
## Залежності
По ідеї всі залежності мають бути вже встановлені на всіх UNIX системах, але ось вони
- grep
- sed
- curl
- zip

## MacOS 
Я не маю змоги тестувати на MacOS, але по ідеї код має працювати так само, як і на Linux, тому можете спробувати

## Видалення

```sh 
rm /usr/bin/hendl
#або якщо встановили в іншу директорію
rm ~/.local/bin/hendl
```
</details>
