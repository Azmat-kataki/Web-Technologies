# Combination Selector:

    article>p{Direct child}*2+main{}

    <body>
        <article>
            <p>Direct child-1</p>
            <p>Direct child-2</p>
            <main>
                <p>Direct child-3</p>
            </main>
        </article>
    </body>


1. Descendent Selector(space): (it means it can access direct and indirect child)

    Parent child{

    }

eg. 
    Article p{
        color: red;
    }

2. Direct child Selector(>)

    article>p{
        color:red;
    }

    article>main>p{
        color:red;
    }




3. Immetiate sibling selector(+)

<body>
    <article>
        <main>
            <p>Indirect child</p>
        </main>
    </article>
    <div> Immetiate sibling </div>
    <span> General Sbiling-2 </span>
    <section> general Sbiling-3 </section>
    <p> General Sibling-4 </p>
</body>

First sibling + Next/Immetiate sibling{ }

article + div{
    color: blue;
}

article + div + span{
    color: red;
}

4. General sibling selector(~): (tilte)

First sibling ~ Any sibling{ }

article ~ p {
    color: pink;
}