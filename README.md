# Basic-C
## Mục lục
- [1. About C Language](#about)
- [2. Feature of C Program](#feature)
- [3. C program structure](#structure)
- [4. C Keywords](#keywords)
- [5. C Character Set](#character)
- [6. Rules for Writing, Compiling and Executing the C program](#rule)
- [7. Data types & Placeholders](#datatype)
- [8. Control characters (Escape sequences)](#controlcharacter)
- [9. Receiving input values from keyboard](#receiving)







<a name = "about"></a>
### 1. About C Language?

Bất kỳ Ngôn ngữ lập trình nào cũng có thể được chia thành hai loại.

- Problem oriented (High level language)
- Machine oriented (Low level language)

C được coi là Middle level Language.

C là modular, portable, reusable

<a name="feature"></a>
### 2. Feature of C Program

- Structured language
    * Nó có khả năng phân chia và ẩn tất cả các thông tin và chỉ dẫn.
    * Mã có thể được phân vùng trong C bằng cách sử dụng các hàm hoặc khối mã.
    * C là một ngôn ngữ có cấu trúc tốt so với ngôn ngữ khác.
- General purpose language
    * Làm cho nó trở thành ngôn ngữ lý tưởng để lập trình hệ thống.
    * Nó cũng có thể được sử dụng cho kinh doanh và ứng dụng khoa học.
    * ANSI đã thiết lập một tiêu chuẩn cho c vào năm 1983.
    * Khả năng của c là thao tác các bit, byte và địa chỉ.
- Portability
    * Khả năng di động là khả năng chuyển hoặc sử dụng phần mềm được viết.
    * Một chương trình C máy tính có thể được sử dụng lại.
    * Bằng cách sửa đổi hoặc không sửa đổi.
- Khả năng tái sử dụng mã & Khả năng tùy chỉnh và mở rộng
    * Một lập trình viên có thể dễ dàng tạo hàm của riêng mình
    * Nó có thể được sử dụng nhiều lần trong các ứng dụng khác nhau
    * Chương trình C về cơ bản tập hợp các chức năng
    * Hàm được hỗ trợ bởi thư viện 'c'
    * Chức năng có thể được thêm vào thư viện 'c' liên tục
- Số lượng từ khóa có hạn
    * Chỉ có 32 từ khóa trong 'C'
    * 27 từ khóa được đưa ra bởi ritchie
    * 5 được thêm bởi ANSI
    * Điểm mạnh của 'C' nằm ở chức năng tích hợp của nó
    * Hệ thống Unix cung cấp số lượng lớn hàm C
    * Một số chức năng được sử dụng trong hoạt động.
    * Khác là chuyên ngành trong ứng dụng của họ
 
<a name= "structure"></a>
### 3. C program structure
```
pre-processor directives
global declarations

main()
{
    local variable deceleration
    statement sequences
    function invoking
}
```
<a name="keywords"></a>
### 4. C Keywords

Từ khóa là những từ mà nghĩa của nó đã được giải thích cho trình biên dịch C. Chỉ có 32 từ khóa có sẵn trong C. Các từ khóa này còn được gọi là 'Reserved words'.
```
auto        double      int         struct 
break       else        long        switch 
case        enum        register    typedef 
char        extern      return      union 
const       float       short       unsigned 
continue    for         signed      void 
default     goto        sizeof      volatile 
do          if          static      while
```
<a name = "character"></a>
### 5. C Character Set

Một ký tự biểu thị bất kỳ bảng chữ cái, chữ số hoặc ký hiệu đặc biệt nào được sử dụng để biểu thị thông tin. Sau đây là các bảng chữ cái, số và ký hiệu đặc biệt hợp lệ được phép sử dụng trong C.
```
Alphabets: A, B,… .., Y, Z a, b, ……, y, z
Digits: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
Special symbols: ~ '! @ #% ^ & * () _ - + = | \ {}
[]:; "'<>,.? /
```
<a name ="rule"></a>
6. Rules for Writing, Compiling and Executing the C program

- C phân biệt chữ hoa chữ thường nghĩa là biến có tên "COUNTER" khác với biến có tên "counter".
- Tất cả các từ khóa đều được viết thường.
- Từ khóa không thể được sử dụng cho bất kỳ mục đích nào khác (như tên biến).
- Mọi câu lệnh C phải kết thúc bằng một dấu `;`. Do đó, hoạt động như một trình kết thúc câu lệnh.
- Ký tự đầu tiên phải là một bảng chữ cái hoặc dấu gạch dưới, không có ký hiệu đặc biệt nào ngoài dấu gạch dưới, không được phép sử dụng dấu phẩy hoặc dấu cách trống trong một biến, hằng số hoặc từ khóa.
- Khoảng trắng có thể được chèn vào giữa hai từ để cải thiện tính dễ đọc của câu lệnh. Tuy nhiên, không có khoảng trống nào được phép trong một biến, hằng số hoặc từ khóa.
- Biến phải được khai báo trước khi nó được sử dụng trong chương trình.
- Tệp phải có phần mở rộng .c
- Chương trình cần được biên dịch trước khi thực thi.

<a name = "datatype"></a>
### 7. Data types & Placeholders

- C có 5 kiểu dữ liệu tích hợp cơ bản.
- Kiểu dữ liệu xác định một tập hợp các giá trị mà một biến có thể lưu trữ cùng với một tập hợp các thao tác có thể được thực hiện trên nó.
- Một biến nhận các giá trị khác nhau tại các thời điểm khác nhau.
- Dạng chung để khai báo một biến là:
`type name;`
- Dưới đây là một ví dụ để sử dụng các biến:
```
#include<stdio.h> 
main() 
{ 
    int sum; 
    sum=12; 
    sum=sum+5; 
    printf("Sum is %d",sum); 
}
```
`printf` hàm sẽ in ra như sau:
`Sum is 17`
Thực tế `%d` là trình giữ chỗ cho giá trị biến số nguyên mà tên của nó đứng sau dấu ngoặc kép.

Các kiểu dữ liệu phổ biến là:
```
int- số nguyên
char- ký tự
long- số nguyên dài
float- số thực
double- số thực dài
```
Các trình giữ chỗ khác là:
```
Placeholders        Format
%c                  Character
%d                  Signed decimal integer
%i                  Signed decimal integer
%e                  Scientific notation[e]
%E                  Scientific notation[E]
%f                  Decimal floating point
%o                  unsigned octal
%s                  String of character
%u                  unsigned decimal integer
%x                  unsigned Hexadecimal (lower)
%X                  unsigned Hexadecimal (upper)
%p                  dispaly a pointer
%%                  print a %
```

<a name = "controlcharacter"></a>
### 8. Control characters (Escape sequences)
Một số ký tự không in được cũng như dấu gạch chéo ngược () và dấu nháy đơn ('), có thể được biểu thị theo escape sequence.
```
\a - Bell
\n - New line
\r - Carriage return
\b - Backspace
\f - Formfeed
\t - Horizontal tab
\" - Quotation mark
\v - Vertical tab
\' - Apostrophe
\\ - Backslash
\? - Question mark
\0 - Null
```
<a name="receiving"></a>
### 9. Receiving input values from keyboard
`scanf` chức năng được sử dụng để nhận đầu vào từ bàn phím.
Dạng chung của hàm `scanf` là:
```
scanf("Format string",&variable,&variable,...); 
```
`Format string` chứa trình giữ chỗ cho các biến mà chúng tôi định nhận từ bàn phím. Một &dấu xuất hiện trước mỗi tên biến trong danh sách biến. Chuỗi ký tự là ngoại lệ từ quy tắc này. Họ sẽ không đến với dấu hiệu này trước họ.

Lưu ý : Bạn không được phép chèn bất kỳ ký tự bổ sung nào trong chuỗi định dạng ngoài phần giữ chỗ và một số ký tự đặc biệt. Nhập ngay cả một khoảng trắng hoặc ký tự không mong muốn khác sẽ khiến chương trình của bạn hoạt động không chính xác và kết quả sẽ không như mong đợi. Vì vậy, hãy đảm bảo rằng bạn chỉ chèn các ký tự giữ chỗ trong chuỗi định dạng scanf. Ví dụ sau nhận nhiều biến từ bàn phím.
```
float a; 
int n; 
scanf("%d%f",&n,&a);
```
Hãy chú ý rằng chức năng scanf không có khả năng kiểm tra lỗi được tích hợp trong nó. Lập trình viên chịu trách nhiệm xác thực dữ liệu đầu vào (loại, phạm vi, v.v.) và ngăn ngừa lỗi


# Basic_C_Plus_Plus

## Mục lục

1. What is C++?
- C ++ là một ngôn ngữ đa nền tảng có thể được sử dụng để tạo ra các ứng dụng hiệu suất cao.
- C ++ được phát triển bởi Bjarne Stroustrup, như một phần mở rộng của ngôn ngữ C.
- C ++ cung cấp cho người lập trình khả năng kiểm soát cao đối với tài nguyên hệ thống và bộ nhớ.

Ngôn ngữ này đã được cập nhật 4 lần chính vào các năm 2011, 2014, 2017 và 2020 lên C ++ 11, C ++ 14, C ++ 17, C ++ 20.

2. Why Use C++?
- C ++ là một trong những ngôn ngữ lập trình phổ biến nhất thế giới.
- C ++ có thể được tìm thấy trong các hệ điều hành ngày nay, Giao diện người dùng đồ họa và các hệ thống nhúng.
- C ++ là một ngôn ngữ lập trình hướng đối tượng mang lại cấu trúc rõ ràng cho các chương trình và cho phép mã được sử dụng lại, giảm chi phí phát triển.
- C ++ có tính di động và có thể được sử dụng để phát triển các ứng dụng có thể thích ứng với nhiều nền tảng.
- C ++ rất thú vị và dễ học!

Vì C ++ gần giống với C # và Java nên lập trình viên dễ dàng chuyển sang C ++ hoặc ngược lại.

3. Difference between C and C++

C ++ được phát triển như một phần mở rộng của C và cả hai ngôn ngữ đều có cú pháp gần như giống nhau.
Sự khác biệt chính giữa C và C ++ là C ++ hỗ trợ các lớp và đối tượng, trong khi C thì không.

C++ is a statically typed,general purpose programming language. C++ was derived C, band is largely based on it.

Note: A programming language is said to used static typing when type checking is performed during compile-time as opposed to run time.

4. Standard Libraries
Standard C++ has three important components

- Core language
Provides all necessary building blocks, including variables, data types, literals, etc.
- Standard library
Offers a rich set of functions for manipulating files, string, etc.
- Standard template library
Offers methods for the manipulation of data structures, etc.

5. First program of C++

Write a program in C++ print a massage on output screen.
```
#include<iostream.h>
using namespace std;
int main()
{
    cout <<"Hello world";
    return();
}
```
6. Program Explanation

- Pound sign(#)
The pound sign(#) at the beginning of a line targets the compiler's pre-processor to include the <iostream.h> header.

  `#include<iostream.h>`

C++ offers verious headers, each of which contains information need for programs to work properly. This particular program calls for the header file <iostream.h>.

The <iostream.h> header define the standard stream objects that input and output data.

- using namespace std;

In our code, the line using namespace std; tells the compiler to use the std (standard) namespace. The std namespace includes features of the C++ standard library.

- main() function

Program execution begins with the main() function. The entry point of every C++ program is main() function.

- Curly brackets {}

Curly brackets {} indicate the beginning and end of a function, which can also be called the function's body. The information inside the brackets indicates what the function does when executed.

- cout<< "Hello world";

cout<< "Hello world"; results in the display of Hello world to output screen.

- cout : is used in combination with the insertion operator

- Insertion operator << : Write the insertion operator as << to insert the data comes after cout into the stream the comes before.

- Semicolon (;)

The semicolon (;) is used to terminate a statement.

- return 0;

The last instruction in the program is the return statement. The line return 0; terminate the main() function and causes it to return value 0 to the calling process.




