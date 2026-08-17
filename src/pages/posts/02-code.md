---
layout: ../../layouts/MarkdownPostLayout.astro
title: "Coding block test"
discription: "A test about coding block"
pubDate: 2026-7-1
author: "Logos"
tags: ["code"]
---
```c
#include <stdio.h>
#include <stdbool.h>

#define stable_connection_ability 10 // not include my family here

struct person{
    bool love_me;
    bool loved_by_me;
    bool independent;
    bool initiative;
};

struct person Connections[stable_connection_ability];

int Index = 3;

int main()
{
    printf("Hello, world!\n");

    int answer = 0;
    struct person p = {false, false, false, false};

    printf("Do you love me?\nInput number to answer 1:yes 0:no\n");
    scanf("%d", &answer);
    if(answer) {
        printf("I love you as well!😆\n");
        p.love_me = true;
    }else {
        printf("I love you anyway.😊\n");
    }

    printf("Have a nice day!🎉\n"); 
    return 0;
}

```
