## Hi there 👋

<!--
**techdiwas/techdiwas** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## About me:
![GitHub_Banner_20250514_184925_0000](https://github.com/user-attachments/assets/148a1e29-12be-45ab-959c-debe408d6414)
My name is **Diwas Neupane**. I'm a nineteen years old computer science enthusiastic person. I'm from a small beautiful country called **Nepal**. I use GitHub to store, build, test, debug and release innovative softwares. I'd like to discover feature rich powerful, beautiful and modern customized operating systems (OSs) made for Android platform. I'm currently using Xiaomi's Redmi 9A smartphone as my daily driver. This smartphone is now old and has stopped receiving updates. Thus, I aim to bring new updates for this smartphone via LineageOS - A free and open-source operating system for various devices, based on the Android mobile platform.

```c
#include <stdio.h>

int main() {
    char name[50], aim[50], edu_level[50];
    int age;

    printf("Enter your age:\n");
    scanf("%d", &age);
    getchar(); // Consume the newline character left by scanf

    printf("Enter your name:\n");
    fgets(name, sizeof(name), stdin);
    name[strcspn(name, "\n")] = '\0'; // Remove trailing newline, if any

    printf("Enter your education level:\n");
    fgets(edu_level, sizeof(edu_level), stdin);
    edu_level[strcspn(edu_level, "\n")] = '\0';

    printf("Enter your aim:\n");
    fgets(aim, sizeof(aim), stdin);
    aim[strcspn(aim, "\n")] = '\0';

    printf("Name=%s\tAge=%d\tEducation Level=%s\tAim=%s\n", name, age, edu_level, aim);
    return 0;
}
```
```md
Output:
Name=Diwas Neupane   Age=19   Education Level=Higher Secondary   Aim=Software engineer
```

- 🔭 I’m currently working on my college projects.
- 🌱 I’m currently learning programming language.
- 👯 I’m looking to collaborate on LineageOS.
- 🤔 I’m looking for help with Android OS development for mt6765 device.
- 💬 Ask me about Custom Roms.
- 📫 How to reach me: `diwasneupane652@gmail.com`
- 😄 Pronouns: he/him
- ⚡ Fun fact: Sky is blue!
