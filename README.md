# csed232-midterm-exam-solved
**TO GET THIS SOLUTION VISIT:** [CSED232 Midterm Exam Solved](https://www.ankitcodinghub.com/product/csed232-object-oriented-programming-midterm-exam-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115674&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSED232 Midterm Exam Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1. 다음은 객체지향 프로그래밍의 중요한 개념들이다. 각각의 개념들이 무엇을 뜻하는지 자세히 기술하시오.

a) Encapsulation

b) Information hiding (or data hiding)

2. 아래와 같은 코드가 있다. MyNameSpace 안의 func2 에서 MyNameSpace 밖의 func 함수를 호출하기 위해서는 어떤 식으로 호출해야 하는지 빈 칸 (a)에 들어갈 코드를 작성하시오.

void func()

{

std::cout &lt;&lt; “Hello” &lt;&lt; std::endl;

} namespace MyNameSpace { void func()

{

std::cout &lt;&lt; “Bye~” &lt;&lt; std::endl;

}

void func2()

{

(a)

}

}

3. 아래와 같은 코드가 있다. 아래 코드에서 Namespace1 에 정의된 함수인 func()를 Namespace2 에 포함시켜서 Namespace2::func() 와 같이 사용하고 싶다. 이때 필요한 코드를 빈칸 (a)에 작성하시오.

namespace Namespace1 { void func()

{

std::cout &lt;&lt; “func()” &lt;&lt; std::endl;

}

void func(int a)

{

std::cout &lt;&lt; “func(int)” &lt;&lt; std::endl;

}

void func(double a)

{

std::cout &lt;&lt; “func(double)” &lt;&lt; std::endl; }

}

namespace Namespace2 { void func2(int a, int b) { std::cout &lt;&lt; “func2(int,int)” &lt;&lt; std::endl; }

(a)

}

int main()

{

Namespace2::func();

Namespace2::func(3); Namespace2::func(3.); return 0;

}

4. 아래의 코드는 main.cpp 를 컴파일할 때 에러가 발생한다. 이 원인은 무엇이고 이를 해결하기 위해서는 어떻게 해야 하는지 기술하시오.

// polar.h

struct polar { double distance, angle; }; struct rect { double x, y; };

// polar_ops.h

#include “polar.h”

rect polar_to_rect(polar p); polar rect_to_polar(rect r);

// main.cpp

#include &lt;iostream&gt;

#include “polar.h”

#include “polar_ops.h”

using namespace std;

int main()

{ rect rplace; polar pplace; cout &lt;&lt; “Enter the x and y values: “; while (cin &gt;&gt; rplace.x &gt;&gt; rplace.y) { pplace = rect_to_polar(rplace);

cout &lt;&lt; “polar: ” &lt;&lt; pplace.distance &lt;&lt; “, ” &lt;&lt; pplace.angle &lt;&lt; endl; cout &lt;&lt; “Next two numbers (q to quit): “;

}

cout &lt;&lt; “Done. “; return 0;

}

5. 다음과 같이 class 와 static method 를 이용하면 namespace 와 비슷한 기능을 흉내 낼 수 있다. 그렇다면 class 와 static method 를 사용하는 것과 비교하였을 때 namespace 를 사용하는 장점은 무엇인가? Namespace 의 장점들을 최대한 많이 기술하시오.

class FakeNamespace

{ public:

static void func(); static void func2(); static void func3();

};

int main()

{

FakeNamespace::func();

return 0;

}

6. 아래의 코드는 문자열을 다루기 위한 간단한 String 클래스이다. main 함수에 있는 예제와 같이 이 클래스의 객체를 기존의 C-style 문자열을 처리하기 위한 strcpy 와 같은 함수에 바로 사용하고 싶다. 그러나 현재에는 이런 것을 가능하게 하는 코드가 빠져 있어서 아래의 코드는 컴파일 에러가 난다. String 객체를 C-style 문자열처럼 다룰 수 있게 하기 위해서 String 클래스에 무엇을 추가해야 하는가? 추가해야 하는 코드를 작성하시오.

#include&lt;iostream&gt;

#include&lt;cstring&gt;

class String { private: char *str; // pointer to string int len; // length of string public:

String(const char *s); // constructor

String(const String &amp;st); // copy constructor

String(); // default constructor

~String(); // destructor

int length() const { return len; }

String &amp;operator=(const String &amp;st);

};

String::String() { len = 0; str = new char[1]; str[0] = ‘’; }

String::String(const char *s)

{ len = std::strlen(s); str = new char[len+1]; std::strcpy(str, s); }

String::String(const String &amp;s)

{ len = s.len; str = new char[len+1]; std::strcpy(str, s.str); }

String::~String() { delete[] str; }

String&amp; String::operator=(const String &amp;st)

{

delete[] str; len = st.len; str = new char[len+1]; strcpy(str, st.str); return *this;

}

int main()

{

String pennywise(“You’ll float too.”); char georgie[100];

std::strcpy(georgie, pennywise); return 0;

}

7. 다음 코드에서 Derived 클래스의 constructor 의 파라미터 중 v_는 Base 클래스로부터 상속받은 v 를 초기화하기 위한 값이고, vv_는 Derived 클래스의 멤버인 vv 를 초기화하기 위한 값이다. 빈 칸 (a) 에 들어갈 코드를 작성하시오.

#include &lt;iostream&gt;

class Base { private: int v; public:

Base(int v_) { v = v_; }

~Base() {}

}; class Derived : public Base { private: int vv; public:

Derived(int v_, int vv_);

~Derived() {}

};

Derived::Derived(int v_, int vv_)

(a)

8. 아래의 코드는 빨간 색으로 표시된 부분에서 컴파일 에러가 발생한다. 이를 수정하기 위해서는 어떻게 해야 하는가? 빈칸 (a)에 들어갈 컴파일 에러를 피하기 위한 코드를 작성하시오.

class IntVector { private:

int *arr; int len; public:

IntVector(int len_) : len(len_), arr(new int[len]) { }

IntVector(const IntVector &amp;v) : len(v.len), arr(new int[len])

{ memcpy(arr, v.arr, sizeof(int) * len); }

IntVector() : len(0), arr(nullptr) { }

~IntVector() { delete[] arr; } int length() const { return len; }

char &amp;operator[](int i)

{

return arr[i];

}

(a)

};

ostream&amp; operator&lt;&lt;(ostream&amp; os, const IntVector&amp; v)

{

for(int i = 0; i &lt; v.length(); i++) os &lt;&lt; v[i] &lt;&lt; ” “; return os;

}

9. C++에서 클래스의 상속을 통해 구현되는 다형성이 무엇인지 자세히 기술하시오. 그리고 이 때 virtual method 를 왜 사용해야 하는지 설명하시오.

10. 다음 코드를 실행하면 코드의 아래에 있는 것과 같은 내용이 출력된다. 빈 칸 (a), (b), (c)에 들어갈 적절한 코드를 작성하시오.

#include &lt;iostream&gt;

class Vehicle { public:

Vehicle() {} virtual ~Vehicle() {} void show() const; protected:

(a)

};

void Vehicle::show() const

{ const int n_wheels = num_wheels();

std::cout &lt;&lt; “Num wheels: ” &lt;&lt; n_wheels &lt;&lt; std::endl;

}

class Sedan : public Vehicle

{ public: Sedan() {} ~Sedan() {} protected:

(b)

};

class Motorcycle : public Vehicle

{ public:

Motorcycle() {} ~Motorcycle() {} protected:

(c)

};

int main()

{

Vehicle *v[2]; v[0] = new Sedan(); v[1] = new Motorcycle();

for(int i = 0; i &lt; 2; i++) v[i]-&gt;show(); delete v[0]; delete v[1]; return 0; }

출력:

Num wheels: 4

Num wheels: 2
