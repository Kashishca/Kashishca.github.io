
<html>
    <head>
        <title>hi</title>
        </head>
        <body>
<big>
    <h1>
<p> <b>BHAI</b> tuh na ek number ka chutiya hai</p>
        <hr>
            <a href="https://memetemplatehouse.com/wp-content/uploads/2020/05/bura-mat-manana-chutiya-toh-tu-hai-meme-template.jpg"><b>Ab dekh kya raha hai,</b> click on me please. </a>
        <hr>
              <hr>  
                
                <p>YEH HAI add in the beggingng for sinlge linked list
    <hr>
 #include <stdio.h>
#include <stdlib.h>
struct node
{
    int data;
    struct node*link;
};

void transversal(struct node*ptr)
{
    while(ptr!=NULL)
    {
        printf("%d\n",ptr->data);
        ptr=ptr->link;
    }
}

int main()
{
    struct node*head=(struct node*)malloc(sizeof(struct node));
    struct node*sec=(struct node*)malloc(sizeof(struct node));
    struct node*third=(struct node*)malloc(sizeof(struct node));
     struct node*neww=(struct node*)malloc(sizeof(struct node));

    int n;
    printf("enter new data");
    scanf("%d",&n);

    head->data=17;
    head->link=sec;

    sec->data=71;
    sec->link=third;

    third->data=99;
    third->link=NULL;

    neww->data=n;
    neww->link=NULL;

    neww->link=head;
    head=neww;

    transversal(head);
    return 0;
}
<hr>
        <hr>
        #include<stdio.h>
 #include<stdlib.h>
 struct node
 {
     int data;
     struct node*link;
 };
 int main()
 {
     printf("Enter no.of nodes to be created\n");
     int n;
     scanf("%d",&n);
     struct node*head=(struct node*)malloc(sizeof(struct node));
     printf("enter itmes\n");
     scanf("%d",&(head->data));
     head->link=NULL;
     struct node*ptr;
     ptr=head;


     for (int i=1;i<n;i++)
     {
         struct node*newnode=(struct node*)malloc(sizeof(struct node));
         scanf("%d",&(newnode->data));
         newnode->link=NULL;
         ptr->link=newnode;
         ptr=ptr->link;
     }
     ptr=head;
     printf("utems are\n");
      while(ptr!=NULL)
     {
         printf("%d\n",ptr->data);
         ptr=ptr->link;
     }
     return 0;
 }

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              
