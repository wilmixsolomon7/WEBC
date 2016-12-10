# WEBC
======

WEBC
====

WEBC  is   a programming  language  invented   by  wilmix  jemin  j   at  year  2016.

WEBC  is   a  stand  alone  programming  language   and  it's  project

is  started   at  year  2004  and  ends  at  year  2016.

WEBC  is  just like OAK  Programming  Langauge...



SYNTAX
======


<WEBC>


<IMPORT>




<%
  
 class <classname>

{

   public void main( )

    {

<! WEBC  program  Logic!>

}  
  
}


%>


?>




ADVANTAGES:
===========

A)  It has  CDollar,GDollar ,  and  JDollar Advantages.

b)  IT  is  the Powerful  and  Best  Standard  Programming Language

than JDollar.



EXAMPLE:
========



<WEBC>


<IMPORT>




<%
  
 class threads

{

   public void main( )

    {

        My thread1 = <NEW> My("thread1: ");

        My thread2 = <NEW> My("thread2: ");

        thread1.<START>; //start thread

        thread2.<START>;  //start thread

        boolean thread1IsAlive = true;

        boolean thread2IsAlive = true;

        do {

           if (thread1IsAlive AND NOTthread1.isAlive()) {

               thread1IsAlive = false;

              WEB.out.println("MY   DOG 1 is dead."); //print it  to the console

           }

           if (thread2IsAlive AND NOTthread2.isAlive()) {

               thread2IsAlive = false;

               WEB.out.println("MY  DOG 2 is dead.");

           }

        } while(thread1IsAlive || thread2IsAlive);

    }

}

 

class My <--- TH

{

Shared <Str> message[] ={ "CDollar", "is", "combination", "of", "JAVA", "and   c"};

 

    public My(<Str> id)

    {

        <SUPER>(id);

    }

 

    public void <RUN>

    {

        SyncOut.displayList("welcome",message);

    }

 

    void randomWait()

    {

        <TRY> {

         <SLEEP>((long)(3000*Math.random())); //simillar sleep  method  in  java

        } <CATCH> (<Interrupted> x) {

           WEB.out.println("Interrupted!");

        }

    }

}

 

class SyncOut

{

public Shared <Synchronized> void displayList(<Str> name,<Str> list[])

{

for(int i=0;i<list.length;++i) {

My t = (My) TH.currentTH();

t.randomWait();

WEB.out.println(name+list[i]);

}

}

} 


  
  


%>


?>





