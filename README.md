# Imitation-team-task-summary-C-language-and-Python-
![image](https://user-images.githubusercontent.com/115389450/233528548-50162c66-b4d7-4190-b5a4-c670e8566073.png)
![image](https://user-images.githubusercontent.com/115389450/233528630-15c0d008-fb63-449b-a017-08844c1a0847.png)
```
#include <stdio.h>

int main(void)
{
    char str1[] = "THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG";
    char str2[] = "ZNK&W[OIQ&HXU]T&LU^&P[SVY&U\\KX&ZNK&RG`_&JUM"; 

    int strLen = sizeof(str1);

    for(int i=0; str1[i] !='\0'; i++)
    {
        printf("%3d %3d %4d\n", str1[i], str2[i], (int)str1[i]-(int)str2[i]); // 기존 문장에서 6조 암호문을 빼고 아스키코드(숫자)로 출력하여 비교하면 암호문 찾을 수 있다.
    }
    printf("\n");

    return 0;
}
```
![image](https://user-images.githubusercontent.com/115389450/233528679-dff4a589-03d0-4ad2-a64e-59f1dd63b3ee.png)
```
#include <stdio.h>

int main(void)
{
    char str1[] = "WE WILL FIND A WAY. WE ALWAYS HAVE";

    int strLen = sizeof(str1);

    for(int i=0; str1[i] !='\0'; i++)
    {
        printf("%c ", str1[i]+6);
    }
    printf("\n");

    return 0;
}
```
![image](https://user-images.githubusercontent.com/115389450/233528710-08644f38-4303-4ef4-a587-7f25b40a2a15.png)
- - -
5조 
- - -
```
#include <stdio.h>

int main(void)
{
    char str1[] = "THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG";
    char str2[] = "VJG\"SWKEM\"DTQYP\"HQZ\"LWORU\"QXGT\"VJG\"NC\\[\"FQI";

    int strLen = sizeof(str1);

    for(int i=0; str1[i] !='\0'; i++)
    {
        printf("%3d %3d %4d\n", str1[i], str2[i], (int)str1[i]-(int)str2[i]);
    }
    printf("\n");

    return 0;
}
```
![image](https://user-images.githubusercontent.com/115389450/233528762-a8feff1d-4c42-4ddc-b133-d9dd752f69c5.png)
```
#include <stdio.h>

int main(void)
{
    char str1[] = "WE WILL FIND A WAY. WE ALWAYS HAVE";

    int strLen = sizeof(str1);

    for(int i=0; str1[i] !='\0'; i++)
    {
        printf("%c ", str1[i]+2);
    }
    printf("\n");

    return 0;
}
```
![image](https://user-images.githubusercontent.com/115389450/233528797-63bba25d-fcfe-4392-8a2b-24028e74d032.png)
- - -
4조
- - -
```
#include <stdio.h>

int main(void)
{
    char str1[] = "THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG";
    char str2[] = "TME\%QZIHK\%BWO\\N%FTX\%JZMUS%O[EW YHJ QA_Y%DTG";

    int strLen = sizeof(str1);

    for(int i=0; str1[i] !='\0'; i++)
    {
        printf("%3d %3d %4d\n", str1[i], str2[i], (int)str1[i]-(int)str2[i]);
    }
    printf("\n");

    return 0;
}
```
![image](https://user-images.githubusercontent.com/115389450/233528849-fd308b98-1e1f-45c3-95c2-5db7b1ce3e28.png)
```
#include <stdio.h>

int main(void)
{
    char str1[] = "WE WILL FIND A WAY. WE ALWAYS HAVE";

    int strLen = sizeof(str1);

    for(int i=0; str1[i] !='\0'; i++)
    {
        if(str1[i]%2!=0)
            printf("%c ", str1[i]);
        else if(str1[i]%2==0)
            printf("%c ", str1[i]+5);
    }
    printf("\n");

    return 0;
}
```
![image](https://user-images.githubusercontent.com/115389450/233528888-59d808e8-19ed-46a1-9f6c-bc86456c4170.png)
```
#include <stdio.h>

int main(void)
{
    char str1[] = "THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG";
    char str2[] = "aUR-^bVPX-O_\\d[-S\\e-WbZ]`-\\cR_-aUR-YNgf-Q\\T";

    int strLen = sizeof(str1);

    for(int i=0; str1[i] !='\0'; i++)
    {
        printf("%3d %3d %4d\n", str1[i], str2[i], (int)str1[i]-(int)str2[i]);
    }
    printf("\n");

    return 0;
}
```
![image](https://user-images.githubusercontent.com/115389450/233528926-7d5844e8-e0c4-4649-a468-86d072641d74.png)
```
#include <stdio.h>

int main(void)
{
    char str1[] = "WE WILL FIND A WAY. WE ALWAYS HAVE";

    int strLen = sizeof(str1);

    for(int i=0; str1[i] !='\0'; i++)
    {
        printf("%c ", str1[i]+13);
    }
    printf("\n");

    return 0;
}
```
![image](https://user-images.githubusercontent.com/115389450/233528974-03d23f95-9de4-4072-a2b6-46e6b789f89b.png)

![image](https://user-images.githubusercontent.com/115389450/233529051-d5ed5555-2098-483d-a5ca-fbe19c5e681b.png)

```
lower = input("소문자를 대문자로 바꿔줄게. 소문자 입력해봐 : ")
case = lower.upper()
print("대문자로 바꾼 후 : ", case)
```
![image](https://user-images.githubusercontent.com/115389450/233529562-803cfb06-1326-4036-b0c7-5d9ecbfcbf5d.png)
![image](https://user-images.githubusercontent.com/115389450/233529583-a6c4b3dc-78e7-47ee-b958-1fe1d0fe13d2.png)
```
english = input("입력한 영어를 아스키코드로 변환해줄게 : ")
makeAscii = []
for character in english:
    makeAscii.append(ord(character))
print("아스키코드로 바꾼 후 : ", makeAscii)
```
![image](https://user-images.githubusercontent.com/115389450/233529607-d552e8a2-5010-4c24-8b27-0c63de9fa7c8.png)





