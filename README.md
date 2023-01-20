ПОДСКАЗКА

/ Console.Write("Введи число: ");
// int limit = int.Parse(Console.ReadLine()!);
// Console.WriteLine($"Колличество цифр {limit} равна {CountNums(limit)}");
// string A = limit.ToString();
// Console.WriteLine($"Колличество цифр {A} равна {CountNums2(A)}");


// -----------МЕТОД сложения-----------
// int GetSum(int A){
//     int sum = 0;
//     for(int i =1; i <= A; i++){
//         sum += i;
//     }
//     return sum; 
// }

// -----------МЕТОД умножения-----------
// int GetMultiply(int N){
//     int mult = 1;
//     for(int i = 1; i <= N; i++){
//         mult = mult * i;
//     }
//     return mult;
// }

// -----------МЕТОД колличества чисел-----------
// int CountNums(int num){
//     int count = 0;
// if(num == 0) return 1;
//     while (num > 0){
//         count++; 
//         num = num / 10;
//     }
//     return count; 
// }

// int CountNums2(string num){
//     int count = num.Length;
//     return count;
// }
//-----------МЕТОД возврат массива-----------
// int[] GetArray(int size){
//    int[] myArray = new int[size];
//    for(int i = 0; i < size; i++){
//        myArray[i] = new Random().Next(5);
//    }
//    return myArray;
//}
//int[] myArray = GetArray(8);
//Console.WriteLine($"[{String.Join(",", myArray)}]");

//-----------МЕТОД массива максимальная и минимальная-----------
//int[] GetArray(int size, int minValue, int maxValue){
//    int[] res = new int[size];
//    for(int i = 0; i < size; i++){
//        res[i] = new Random().Next(nimValue, maxValue +1);
//    }
//    return res;
