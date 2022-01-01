![Photo](https://avatars.githubusercontent.com/u/65305046?s=400&u=5bf7a3f329dd20510fe34de50761a31ff8b58559&v=4)

# Dmitry Shashkov

## Contacts:
    E-mail: shashkovdg@gmail.com
    GitHub: ShashkovDG
    Discord name for rs-school: Dmitry (@ShashkovDG)

## About me:
    I have never worked in the field of information technology, but I have always been interested in this field since the advent of
    the first computer. I attended computer science courses at school. At university, my classes were related to computer science,
    but with an emphasis on economics. Unfortunately for myself, I recently delved into programming. Before the courses, I only
    studied HTML on my own, and in addition to the duties of the manager, I additionally used the employer's website, I was engaged
    in filling the site. From 2018 to 2020, I took programming courses in C, C++, C# and underwent professional retraining. As a
    result, I ran into problems when writing software, since the C# language itself and especially the UWP platform I wrote on were
    created relatively recently and there is very little information in Russian, and I know English very poorly and mostly use a
    translator. After a long search for information and reading documentation in English, I lost the desire to do programming. But
    after a while I found out about the RS SCHOOL courses and decided to try myself in the field of web programming.

## Skills:
    Basics of languages: C, C++, C#. The Universal Windows Platform, which also uses the XML language. ADO.NET and SQL. ASP.NET where
    HTML and CSS were also studied.

## Code example:
```

    // Maybe not very smart, but encryption was invented by me personally for my program

    //I implemented it so that during authorization it was possible to save the password to a file, but after opening this file
    locally, instead of the password there was an encrypted text of characters

    // later I decided that all the text in the program and in its chat should be encrypted before writing to the database so that
    the data can be read only through the program

    int[] key = { 2, 4, 0, 7, 8, 5 }; // I use my date of birth as a key, but any other combinations of any size can be used

    // Text encryption
    private int[] Encryption(string str, int[] key)
    {
        int i = 0;
        int j = 0;
        int[] temp = new int[str.Length];
        foreach (char ch in str)
        {
            int n = Convert.ToInt32(ch);
            if (i == num.Length) i = 0;
            if (i % 2 == 0) n += key[i++];
            else n -= key[i++];
            temp[j++] = n;
        }
        return temp;
    }

    // Decryption to text
    public string Decryption(int[] temp, int[] key)
    {
        int i = 0;
        string str = "";
        foreach (int n in temp)
        {
            if (i == num.Length) i = 0;
            if (i % 2 == 0) t -= key[i++];
            else t += key[i++];
            str += Convert.ToChar(n);
        }
        return str;
    }

```

## Work experience:
    No work experience. Since during the training we were only mentioned about Git and GitGub, but not trained, at the time of writing
    the program, the version control system was not used. Perhaps I will add my project created on UWP later.

## Education:
    Russian State University of Tourism and Service, Moscow, 2003-2008, Qualification computer scientist - economist in the specialty
    "Applied computer science in economics". Bauman Moscow State Technical University, Moscow, 2018-2020, Professional retraining in
    the program "Programming in C/C++/C#".

## English language
    The level of language proficiency is very low. I use a translator.
