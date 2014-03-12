X.JS
===========
       true;true;             true;true;
        true;cons=           console;1;
         r=function         (tn,stra,l
         ){return new      Array(tn+1
          ).join(stra     )};l=s=5;p
           =0;i=1;ne =false;while(i<
            8){p+=1;if(!ne&&s<=0){
             ne=true;}str='';ts=s>
            0?(r(s-1,' ')):'';if
           (!(p>=4))     {str+=r(p,
          ' ')+r(l,      '#')+ts+r(l,
         '#');cons        .log(str)}if
        (ne){s+=2;          p-=2;true;}
        else{s-=2;          }i+=1;};true;


It's code in the shape of an X, that when executed, prints out an X :)

This was actually a lot harder than it looks. It also creates a weird pattern
when you stack it the same code multiple times (see dna.js)