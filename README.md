## Ana Damjanoska 196080

## Control Flow Graph

![controlflowgraph drawio](https://github.com/anadamjanoska/SI_2023_lab2_196080/assets/130085738/b3312831-4b44-45cc-b794-64c7860a6e50)

## Цикломатска комплексност
Цикломатската комплексност = 11 и таа може да се пресмета на три начини:
1. Користејќи ја формулата e-v+2: 35 - 26 + 2 = 11
2. Користејќи ја формулата P+1 = 10 + 1 = 11, каде P - бројот на предикатни јазли 
3. Броејќи региони: 10 + 1 = 11

## Every Branch критериум
1. User = null. Задачата треба да фрли RuntimeException.
2. User = [Ana, abc123456789!, ana,damjanoska@yahoo.com]. User има username, password и email што ги задоволуваат сите услови и во 
листата нема идентичен корисник.
3. User = [null, 123, ana.damjanoska@yahoo.com] - User има username null, password-от е помал од 8 цифри и email-от е идентичен со 
email од друг корисник.
4. User = [Ana, pass word, anadamjanoska@yahoo.com] - User има ист username како и друг корисник, password-от содржи празно место, а email
адресата е точна.
5. User = [AnaDamjanoska, abcdefghi, ana.damjanoska] - User има точно username, password-от нема специјални карактери и email адресата
не е точна (не содржи @).


