
تهيئة بيئة العمل فى تيرمكس 🤠⚡

apt update && apt upgrade -y && pkg install fish && pkg install figlet && pkg install nano && cd .. && cd usr/etc && nano zshrc
ثانيًا، نقوم بمسح كل ما فى الملف ولصق هذا الكود الجديد :

emulate sh -c  . /data/data/com.termux/files/usr/etc/profile 
command_not_found_handler() {
 /data/data/com.termux/files/usr/libexec/termux/command-not-found $1
}
clear
figlet -f big Frost
fish
ثالثًا، نقوم بحفظ الملف وخروجه باستخدام الأوامر التالية:
CTRL + x
y
Enter
رابعًا، نقوم بإعادة تشغيل تريمكس باستخدام الأمر التالي:

exit
❗ ملاحظة:
يرجى استبدال كلمة { Frost } التى تحتها خط فى الكود بالإسم الذى تريده أن يظهر معك واستبدال كلمة { big } بإسم الخط الذى يناسبك.

أسماء أفضل الخطوط:
1- standard
2- big
3- block
4- digital
5- bubble
✦•━━━━━━━━━━━━━•✦
⚠️ لا تستخدم الشرح في ما لا يرضي الله
✦•━━━━━━━━━━━━━•✦
  ♡   ‌ ‌      ❍ㅤ         ⎙ㅤ    ‌     ⌲ 
 ˡᶦᵏᵉ ‌   ᶜᵒᵐᵐᵉⁿᵗ       ˢᵃᵛᵉ         ˢʰᵃʳ
