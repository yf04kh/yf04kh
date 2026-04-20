<div align="center">

<img src="https://github.com/SP-XD/SP-XD/blob/main/images/hellocoders_rounded.gif?raw=true" alt="Hello Coders" width="60%"/> <br>
<img src="https://github.com/SP-XD/SP-XD/blob/main/images/dev-working_rounded.gif?raw=true" alt="Workspace"  width="40%"/><br> 

![Totals Hits](https://komarev.com/ghpvc/?username=yf04kh&style=flat&color=orange&label=PROFILE+VIEWS) <br><br>
[![Telegram](https://img.shields.io/badge/Telegram-grey?style=flat&logo=telegram)](https://t.me/yf04kh)
[![Instagram](https://img.shields.io/badge/Instagram-grey?style=flat&logo=instagram)](https://www.instagram.com/yf04kh)
[![Facebook](https://img.shields.io/badge/Facebook-grey?style=flat&logo=facebook)](https://www.facebook.com/share/1bJfwwd4NC/)
<br>
</div>

<hr></hr>

### 🚀 Tech Stack & Tools
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat&logo=markdown&logoColor=white)
![Vscode](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=flat&logo=visual%20studio%20code&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=flat&logo=git&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
![GNU/Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

```cpp
#include <iostream>
#include <string>

struct Developer {
    std::string name = "Yousef Thair";
    std::string major = "Computer Science";
    std::string university = "University of Technology";
    std::string currentFocus = "Mastering C++";
    
    void printIntro() {
        std::cout << "Hello World! I'm " << name << ", studying " << major << ".\n";
        std::cout << "Currently diving deep into " << currentFocus << " and building logical solutions." << std::endl;
    }
};

int main() {
    Developer yousef;
    yousef.printIntro();
    return 0;
}
