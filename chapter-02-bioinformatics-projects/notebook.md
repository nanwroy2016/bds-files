# *Zea Mays* SNP Calling
## *Zea Mays* SNP Calling

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

*   Red
*   Green
*   Blue  




We sequenced three lines of *zea mays*, using paired-end
sequencing. This sequencing was done by our sequencing core and we
received the data on 2013-05-10. Each variety should have **two**
sequences files, with suffixes `_R1.fastq` and `_R2.fastq`, indicating
which member of the pair it is.

## Sequencing Files

All raw FASTQ sequences are in `data/seqs/`:

    $ find data/seqs -name "*.fastq"
    data/seqs/zmaysA_R1.fastq
    data/seqs/zmaysA_R2.fastq
    data/seqs/zmaysB_R1.fastq
    data/seqs/zmaysB_R2.fastq
    data/seqs/zmaysC_R1.fastq
    data/seqs/zmaysC_R2.fastq

## Quality Control Steps

After the sequencing data was received, our first stage of analysis
was to ensure the sequences were high quality. We ran each of the
three lines' two paired-end FASTQ files through a quality diagnostic
and control pipeline. Our planned pipeline is:

1. Create base quality diagnostic graphs.
2. Check reads for adapter sequences.
3. Trim adapter sequences.
4. Trim poor quality bases

Recommended trimming programs:

 - Trimmomatic
 - Scythe


This is a normal paragraph:   
    This is & a code block.
    This is a code block.
    This is a code block.
    

This is the end

This is <a href="https://www.w3schools.com/">Visit W3Schools.com!</a> website URL.

This is [Visit W3Schools.com!](https://www.w3schools.com/ "W3Schools") website URL.


## This is an inline link
I get 10 times more traffic from [Google](http://google.com/ "Google")
than from [Yahoo](http://search.yahoo.com/ "Yahoo Search") or
[MSN](http://search.msn.com/ "MSN Search").


## This is an example of reference link
I get 10 times more traffic from [Google][1] than from
[Yahoo][2] or [MSN][3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

  ## This is implicit link name shortcut
  I get 10 times more traffic from [Google][] than from
 [Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"


  <p>I get 10 times more traffic from <a href="http://google.com/"
title="Google">Google</a> than from
<a href="http://search.yahoo.com/" title="Yahoo Search">Yahoo</a>
or <a href="http://search.msn.com/" title="MSN Search">MSN</a>.</p>


<em>This text is emphasized</em>

*This text is emphasized*

_This text is emphasized_



<strong>This text is important!</strong>

**This text is important!**

__This text is important!__

Use the `printf()` function.

````There is a literal backtick (`) here.````
<p><code>There is a literal backtick (`) here.</code></p>


A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``

## Use url for image link
<img src="https://www.w3schools.com/html/pic_trulli.jpg" alt="Trulli" width="500" height="333">

![Trulli](https://www.w3schools.com/html/pic_trulli.jpg)


#Use full path

<img src="../pic_trulli.jpg" alt="Trulli" width="500" height="333">


![Trulli](../pic_trulli.jpg)

[Hello World](#11-hello-world)



> ## 1.1 Hello World 
> >-this is for ****testing**** purpose

