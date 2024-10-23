1. Simple Selector:
        i. Tag name selector
                div{
                    color: red;
                }

        ii. Id selector(#)
                #div{
                    color:red;
                }

        iii. class selector
                .flex{
                    color: purple;
                }

        iv. Universal selector(*) :(CSS boiler Plate)(* means all elements)
                *{
                    margin:0;
                    padding:0;
                    box-sizing: border-box
                }
                
        v. Grouping Selector(,)

            <div>Div tag </div>
            <p>Div tag </p>
            <span>Div tag </span>
            <main>Div tag </main>

            
                div,main{
                    color; salmon;
                }
        