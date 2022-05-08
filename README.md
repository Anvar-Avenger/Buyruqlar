# Git
1. cd HududGaz
2. git init
3. git add .
4. git commit -m "Birinchi"

### Mahalliy ombor bilan ishlash
1. ``git add <file_name>`` git ro'yxatiga fayl qo'shish
2. ``git commit -m "Izoh"`` git omboriga faylni saqlash

### Masofaviyga ulash
1. ``git branch -M main``  -- joriy filialni o'rniga "main" ni yaratadi
2. ``git remote add origin https://github.com/Anvar-Avenger/HududGaz.git`` masofaviy omborga ulash
3. ``git push -u origin main`` -- main filialiga fayllarni yuklash
3. ``git push -f origin main`` -- 3 - chi ishlamasa

### Birlamchi filial
git branch -M main default

### Masofaviy ishlash
1. ``git pull`` loyihani yangilash uchun
2. ``git commit -m "Izoh" --`` mahalliy omborga saqlash
3. ``git push -u origin main`` -- masofaviy omborning main filialiga yuklash


## Gitda holatlar
- ``git status`` -- git dagi fayllar holati
- ``git remote`` -- masofaviy serverga ulanganini tekshirish


## Hisob bilan ishlash
- ``git --version`` - git naqli (versiyasi)
- ``git config``
- ``git config --global user.name <Nom>`` - foydalanuvchini kiritish
- ``git config --global user.email <Pochta>`` - pochtani kiritish
- ``git config user.email`` - pochtani ko'rish

## Qo&#8216;shimcha
- Qo&#8216;shilgan faylni o&#8216;ni o&#8216;chirish
    ``
        git rm --cached <file>
    ``
  
## Gitdan chiqish
* Chiqish  (yangi qatordan yozilishi uchun 2 ta bo&#8216;shliq yozilgan)  
   ``
   rmdir .git
   ``
* Chiqish  
   ``
   rmdir /s .git
   ``

### Havola
https://gitbetter.substack.com/p/how-to-change-git-default-branch?s=r
