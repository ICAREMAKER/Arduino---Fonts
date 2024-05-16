# Arduino---Fonts ![arduinoThumb](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/1e80c0a0-27bd-4b96-a6e1-88ef7eca9098) ![C++-Logo wine](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/882aa901-1f05-43d5-9574-60db4e7b6537)





![led](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/9b486ca7-b6de-4f59-b378-a2420ee5effe)


## Chiffre 0
![0](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/6b96274b-6c39-4ad4-8e57-7f9968b47d90)

```C
void ZERO()
{
	byte image0[] =
{
   B00000000,  
   B01111110,
   B11111111,
   B10100001,
   B10010001,
   B11111111,
   B01111110,
   B00000000
};

  for (int i = 0; i < 8; i++)  
  {
    lc.setRow(0,i,image0[i]);
  }
}


```
## Chiffre 1
![1](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/1088bbad-da11-4662-b2e7-a5689dbb768a)

 ```C
void UN()
{
  byte image1[] =
{
   B00000000,  
   B00000000,
   B10000100,
   B11111110,
   B11111111,
   B10000000,
   B00000000,
   B00000000
};
  for (int i = 0; i < 8; i++)
  {
    lc.setRow(0,i,image1[i]);
  }
}
```
## Chiffre 2
![2](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/294aeadf-ec10-41d8-8bdc-544a334ee61b)

```C
void DEUX()
{
  byte image2[] =
{
   B00000000,   
   B10000010,
   B11000011,
   B11110001,
   B10111001,
   B10011111,
   B10001110,
   B00000000
};
  for (int i = 0; i < 8; i++)
  {
    lc.setRow(0,i,image2[i]);
  }
}
```
## Chiffre 3
![3](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/a2769043-5e9d-4d65-99fd-5a433ffd1d07)

```C
void TROIS()
{
  byte image3[] =
{
   B00000000,   
   B01000010,
   B11000011,
   B10000001,
   B10001001,
   B11111111,
   B01110110,
   B00000000
};
  for (int i = 0; i < 8; i++)
  {
    lc.setRow(0,i,image3[i]);
  }
}
```
## Chiffre 4
![4](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/cb74eb45-ba16-4243-8b69-ea338aefd30a)

```C
void QUATRE()
{
  byte image4[] =
{
   B00000000,  
   B00011110,
   B00011111,
   B00010000,
   B11111100,
   B11111100,
   B00010000,
   B00000000
};
  for (int i = 0; i < 8; i++)
  {
    lc.setRow(0,i,image4[i]);
  }
}
```
## Chiffre 5
![5](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/e2111ec2-fbcc-4a23-8114-207da1faaf18)

```C
void CINQ()
{
	byte image5[] =
{
   B00000000,  
   B01001111,
   B11001111,
   B10001001,
   B10001001,
   B11111001,
   B01110001,
   B00000000
};

  for (int i = 0; i < 8; i++)
  {
    lc.setRow(0,i,image5[i]);
  }
}

```
## Chiffre 6
![6](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/f4255e43-ae18-4c98-8bbc-1649b267627d)

```C
void SIX()
{
	byte image6[] =
{
   B00000000,   
   B01111110,
   B11111111,
   B10010001,
   B10010001,
   B11110011,
   B01100010,
   B00000000
};

  for (int i = 0; i < 8; i++)
  {
    lc.setRow(0,i,image6[i]);
  }
}
```
## Chiffre 7
![7](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/b0b2ccbf-3e83-4fb8-adbf-a47b616cf597)

```C
void SEPT()
{
	byte image7[] =
{
   B00000000,  
   B00000001,
   B00000001,
   B11100001,
   B11111001,
   B00011111,
   B00000111,
   B00000000
};

  for (int i = 0; i < 8; i++)
  {
    lc.setRow(0,i,image7[i]);
  }
}
```
## Chiffre 8
![8](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/c2c7d47c-3566-4c69-a52b-cf8f90e82397)

```C
void HUIT()
{
	byte image8[] =
{
   B00000000,  
   B01100110,
   B11111111,
   B10001001,
   B10010001,
   B11111111,
   B01100110,
   B00000000
};

  for (int i = 0; i < 8; i++)
  {
    lc.setRow(0,i,image8[i]);
  }
}
```
## Chiffre 9
![9](https://github.com/ICAREMAKER/Arduino---Fonts/assets/107696317/bdabd3a7-f29c-4d4e-b480-4724dad36c4d)

```C
void NEUF()
{
	byte image9[] =
{
   B00000000,   
   B01000110,
   B11001111,
   B10001001,
   B10001001,
   B11111111,
   B01111110,
   B00000000
};

  for (int i = 0; i < 8; i++)
  {
    lc.setRow(0,i,image9[i]);
  }
}
