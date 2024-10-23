# Pseudo class selector(:)

<Article>
    <p>Paragraph tag-1</p>
    <p>Paragraph tag-2</p>
    <p>Paragraph tag-3</p>
    <p>Paragraph tag-4</p>
    <p>Paragraph tag-5</p>
</article>

1. :first-child

    article > p:first-child{
        color: red;
    }

2. :last-child

    article p:last-child{
        color: blue;
    }

3. :nth-child()

    article :nth-child(3){

    }

4. :nth-last-of-type()

    article span:nth-last-of-type(2){
        
    }