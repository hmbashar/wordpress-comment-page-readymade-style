# wordpress-comment-page-readymade-style
You may use this css for your wordpress blog comment design.


# Default WordPress Comments Classes

```
/*Comment Output*/
 
.commentlist .reply {}
.commentlist .reply a {}
 
.commentlist .alt {}
.commentlist .odd {}
.commentlist .even {}
.commentlist .thread-alt {}
.commentlist .thread-odd {}
.commentlist .thread-even {}
.commentlist li ul.children .alt {}
.commentlist li ul.children .odd {}
.commentlist li ul.children .even {}
 
.commentlist .vcard {}
.commentlist .vcard cite.fn {}
.commentlist .vcard span.says {}
.commentlist .vcard img.photo {}
.commentlist .vcard img.avatar {}
.commentlist .vcard cite.fn a.url {}
 
.commentlist .comment-meta {} 
.commentlist .comment-meta a {}
.commentlist .commentmetadata {}
.commentlist .commentmetadata a {}
 
.commentlist .parent {}
.commentlist .comment {}
.commentlist .children {}
.commentlist .pingback {}
.commentlist .bypostauthor {}
.commentlist .comment-author {}
.commentlist .comment-author-admin {}
 
.commentlist {}
.commentlist li {}
.commentlist li p {}
.commentlist li ul {}
.commentlist li ul.children li {}
.commentlist li ul.children li.alt {}
.commentlist li ul.children li.byuser {}
.commentlist li ul.children li.comment {}
.commentlist li ul.children li.depth-{id} {}
.commentlist li ul.children li.bypostauthor {}
.commentlist li ul.children li.comment-author-admin {}
 
#cancel-comment-reply {}
#cancel-comment-reply a {}
```
## Adding Odd and Even Background Colors for Comments
Having a different background color for odd and even comments is a design trend that has been around for some years now. It helps the readability specially if you have a lot of comments. It also looks really good with certain theme colors which is why many designers want to utilize this functionality. To help designers achieve this goal, WordPress adds an odd and even class to each comment respectively.

You can easily add the odd/even styling for comments in your theme’s style.css by pasting the following code.

```
.commentlist .even .comment { 
background-color:#ccddf2; 
} 
.commentlist .odd .comment {
background-color:#DDD;
}
```
![alt text](http://cdn.wpbeginner.com/wp-content/uploads/2013/03/even-odd-comments.jpg)


## Styling Comment Author and Meta Information

```
.comments-area article header {
    margin: 0 0 48px;
    overflow: hidden;
    position: relative;
    background-color:#55737D;
    color:#FFFFFF;
    padding: 10px;
}
```
This is how it should look like: 
![alt text](http://cdn.wpbeginner.com/wp-content/uploads/2013/03/comment-meta-css.jpg)


[Credit with details here](http://www.wpbeginner.com/wp-themes/how-to-style-your-wordpress-comments-layout/)
