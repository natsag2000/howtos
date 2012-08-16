БИЧИЛ ЗААВАРЧИЛГААНУУД
======================

Бүрхүүл дотроо дараах зааврыг нэмнэ

*zsh*

> ho () { curl https://raw.github.com/natsag2000/howtos/master/howto-$* }

> howto () { curl https://raw.github.com/natsag2000/howtos/master/howto-$* }

*tcsh*

> alias howto 'curl https://raw.github.com/natsag2000/howtos/master/howto-\!*'

> alias ho 'curl https://raw.github.com/natsag2000/howtos/master/howto-\!*'


ингээд бүрхүүлээс дараах маягаар дуудаж хэрэглэнэ

> howto list

> howto gpg

> ho openssl

> ho tunnel

гэх мэт.

*АНХААР:*
  curl програм суугдсан байх ёстой.

*TODO:*
  Илүү их заавар оруул
