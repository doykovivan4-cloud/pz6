# Практическая работа №6
<img width="990" height="343" alt="image" src="https://github.com/user-attachments/assets/7b5302a5-5ada-4b15-8562-23a4b54572af" />

# Задача 1. Перевод времени
cin >> hours; 
cout << hours * 60 << " минут"

# Задача 2. Сравнение чисел
 cin >> A >> B;
    if (A > B) {
        cout << "Число A больше"
    } else {
        cout << "Число B больше"
        
# Задача 3. Допуск к экзамену
 cin >> grade;
  if (grade >= 3) {
        cout << "Допущен" 
    } else {
        cout << "Не допущен"
    
# Задача 4. Скидка в магазине
 int total = price * quantity; 
 if (total > 1000) { 
        total = total - (total / 10);
    }
cout << "Итоговая сумма к оплате: " << total << " руб.";

# Задача 5. Решение квадратного уравнения
if (a == 0) {
        cout << "Уравнение не является квадратным";
 int D = b * b - 4 * a * c;

   if (D < 0) {
        cout << "Корней нет";
    } else if (D == 0) {
        int x = -b / (2 * a);
        cout << "Один корень: " << x;
    } else {
        int sqrtD = static_cast<int>(sqrt(D));
        int x1 = (-b + sqrtD) / (2 * a);
        int x2 = (-b - sqrtD) / (2 * a);
        cout << "Два корня: " << x1 << " и " << x2;
