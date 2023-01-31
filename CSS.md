
# Css interview question and answer

 


1. what is the box model in css ? which css property are a part of it?

ans-  A rectangle box is wrapped around every html element . the box model is used to detemine the height & width of box .
        css box consist of width and height ,padding border, margin.
        content-> padding->border->margin

2. what are the merit of using css?

ans- #separation of content from presentation 
            css provides a way to present the same content in multiple presentation formats in mobile or desktop or laptop.

        # easy to maintain 
        # bandwidth
        used effectively,
        css style sheet will be stored in the browser cache and they can be used on multiple pages , without having download again.


3. what are the limitation of css?

ans- Browser compatibility : Some style selector are supported and some are not . we have to determine which style is supported or not using the 
         @support

         Cross browser issues : some selector behave differently in different browser.
         There is no parent selector: currently , using css , you can't select a parent tag.


4. How to include css in the webpages ?

 1. external css
 2. Embed css
 3. inline css
4. @import stylesheet   @import "path"



5. what are the different type of selector in css?

#1. Universal 
#2. ElementType
#3. Id selector
#4. class selector
#5. Descendant combinator (combinator two or more selector)
#6. Child combinator
#7. General sibling combinator
#8. adjacent sibling combinator
#9. Attributes selector


6. what are the css preprocessor?
  what are sass,less,and stylus?
  why people use them?

  ans- search on google.


7. what is VH/Vw in css?
ans- its a css unit to measure the height and width in percentage with respect to viewport.
     it is mainly used in responsive web design techniques. 
     1 VH = 1/100 of the height of viewport.
     1000px = 1vw = 1vh


8. reset vs normal css , how do they differ?
ans-  reset css aim to remove all built in browser styling . 
        normal css aims to make built in browser styling consistent across browser . it also corrects bugs for common browser deendency.

9. inline VS inline-block vs block?
ans- just google it.

10. is it important to test the webpage in diffrent browser?
ans- just google it

11. what are pseudo element and pseudo classes?
ans- 
    #1. pseudo element : allow us to create item that do not exist in the document tree.
            ::before
            ::after
            ::first-letter
            ::first-line

    #2. pseudo class : select regular element but under certain condition 
          :link
          :hover
          :active
          :focus
          :visited
    


12. How do you specify units in the css? diffrent ways to do it?
ans-  like ps,em,pt,%.


13. does margin top and bottom effect on inline element?
ans- no, inline element flow with the contents of the page.

14. what property is used for chaging the font face?

  ans-  font -family: 'Arial';



15.  Adaptive Design VS Responsive Design?
ans - just google it.

16. How are the css selector matched against the element by the browser?
ans- from Right to left.


17.   Border box VS content-box?
ans -  border-box includes content , padding, border .
            content-box   exclude padding and border.

18. How to use opacity in css?
   div {

      opacity:0.6;

      filter:alpha(opacity-60);

   }


19. why we should use float property in css?
ans- the float propery is used for positioning the element horizontaly either left or right.


20. what is a z-index?
=====================================================
21. please get these selector means?

#1.  div , p : this selector means select all div & p element.
#2. div p : this selector tells to select all p element that are inside div element.
#3. div ~ p : this selector tells to select all p element that have div element preceeded anywhere.
#4. div+p : select all p element placed immediately after div element .
#5. div >p :select all p elemnt which has div as an immediate parent 

==============================================================
        
21. what are the properties of Flexbox? - 2017
ans - #1. flex-direction: helps to define your container direction.
            row , column , row-reverse , column-reverse.
        #2. flex-wrap: it define that flex-item should be wrapped or not .
         wrap ,nowrap,wrap-reverse
         #3. flex-flow : this is used setting both flex-direction and flex-wrap.
         #4. justify-content : used to aligning the flex-item .
                center , flex-start , flex-end ,space-around , space-between ,align-items , 
                align-content :this is used for aligning the flex lines.


22.  what is cascading in css?
ans- just google it.







