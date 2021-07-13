# 这是设计思维大作业的第一个版本
> 今后如果需要搞把它搞成双创的话这个版本还是太捞
> 交作业加油!
没有更多的话要说?

# 关于使用GitHub进行合作的中文博客
> 引自知乎
<div class="ContentItem AnswerItem" data-za-index="0" data-zop="{&quot;authorName&quot;:&quot;李鼎(哲良)&quot;,&quot;itemId&quot;:74250205,&quot;title&quot;:&quot;GitHub 的 Fork 是什么意思？&quot;,&quot;type&quot;:&quot;answer&quot;}" name="74250205" itemprop="acceptedAnswer" itemtype="http://schema.org/Answer" itemscope="" data-za-detail-view-path-module="AnswerItem" data-za-detail-view-path-index="0" data-za-extra-module="{&quot;card&quot;:{&quot;has_image&quot;:false,&quot;has_video&quot;:false,&quot;content&quot;:{&quot;type&quot;:&quot;Answer&quot;,&quot;token&quot;:&quot;74250205&quot;,&quot;upvote_num&quot;:336,&quot;comment_num&quot;:24,&quot;publish_timestamp&quot;:null,&quot;parent_token&quot;:&quot;20431718&quot;,&quot;author_member_hash_id&quot;:&quot;bedda99377f438b0eec58385e93d1d64&quot;}}}"><div class="ContentItem-meta"><div class="AuthorInfo AnswerItem-authorInfo AnswerItem-authorInfo--related" itemprop="author" itemscope="" itemtype="http://schema.org/Person"><div class="AuthorInfo"><meta itemprop="name" content="李鼎(哲良)"><meta itemprop="image" content="https://pic2.zhimg.com/4e79911f2_l.jpg?source=1940ef5c"><meta itemprop="url" content="https://www.zhihu.com/people/oldratlee"><meta itemprop="zhihu:followerCount" content="324"><span class="UserLink AuthorInfo-avatarWrapper"><div class="Popover"><div id="Popover14-toggle" aria-haspopup="true" aria-expanded="false" aria-owns="Popover14-content"><a target="_blank" class="UserLink-link" data-za-detail-view-element_name="User" href="//www.zhihu.com/people/oldratlee"><img class="Avatar AuthorInfo-avatar" width="38" height="38" src="https://pic2.zhimg.com/4e79911f2_xs.jpg?source=1940ef5c" srcset="https://pic2.zhimg.com/4e79911f2_l.jpg?source=1940ef5c 2x" alt="李鼎(哲良)"></a></div></div></span><div class="AuthorInfo-content"><div class="AuthorInfo-head"><span class="UserLink AuthorInfo-name"><div class="Popover"><div id="Popover15-toggle" aria-haspopup="true" aria-expanded="false" aria-owns="Popover15-content"><a target="_blank" class="UserLink-link" data-za-detail-view-element_name="User" href="//www.zhihu.com/people/oldratlee">李鼎(哲良)</a></div></div></span></div><div class="AuthorInfo-detail"><div class="AuthorInfo-badge"><div class="ztext AuthorInfo-badgeText">软件工程师|Git工作流指南翻译者|GitHub频繁使用者|Vimer</div></div></div></div></div></div><div class="LabelContainer-wrapper"></div><div class="css-h5al4j"><span><span class="Voters"><button type="button" class="Button Button--plain">336 人赞同了该回答</button></span></span></div></div><meta itemprop="image"><meta itemprop="upvoteCount" content="336"><meta itemprop="url" content="https://www.zhihu.com/question/20431718/answer/74250205"><meta itemprop="dateCreated" content="2015-11-27T14:27:39.000Z"><meta itemprop="dateModified" content="2021-05-05T17:12:26.000Z"><meta itemprop="commentCount" content="24"><div class="RichContent RichContent--unescapable"><div class="RichContent-inner"><span class="RichText ztext CopyrightRichText-richText" itemprop="text"><p><b>简单的说明：</b></p><p>GitHub中Fork 是 <b><i>服务端的代码仓库克隆</i></b>（即 新克隆出来的代码仓库在远程服务端），包含了原来的仓库（即upstream repository，上游仓库）所有内容，如分支、Tag、提交。代码托管服务（如Github、BitBucket）提供了方便的完成Fork操作的功能（在仓库页面点一下Fork按钮）。</p><p>这样有了一个你<b><i>自己的 </i></b>可以自由提交的远程仓库，然后可以通过的 <b>Pull Request </b>把你的提交<b><i>贡献回 </i></b>原仓库。而对于原仓库Owner来说，鼓励别人Fork他的仓库，通过Pull Request 能给他的仓库<b><i>做贡献</i></b>，也是提升了原仓库的<b><i>知名度</i></b>。</p><p>要更多地了解GitHub中Fork ，参见本人的中文译文：</p><p>1.《Forking工作流》 <a href="https://link.zhihu.com/?target=https%3A//github.com/oldratlee/translations/blob/master/git-workflows-and-tutorials/workflow-forking.md" class=" wrap external" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">github.com/oldratlee/translations/git-workflows-and-tutorials/workflow-forking.md</a></p><figure data-size="normal"><noscript><img src="https://pic2.zhimg.com/50/v2-ba2bd4a27309817623b56acae1939767_hd.jpg?source=1940ef5c" data-caption="" data-size="normal" data-rawwidth="400" data-rawheight="344" class="content_image" width="400"/></noscript><img src="https://pic2.zhimg.com/80/v2-ba2bd4a27309817623b56acae1939767_720w.jpg?source=1940ef5c" data-caption="" data-size="normal" data-rawwidth="400" data-rawheight="344" class="content_image lazy" width="400" data-actualsrc="https://pic2.zhimg.com/50/v2-ba2bd4a27309817623b56acae1939767_hd.jpg?source=1940ef5c" data-lazy-status="ok"></figure><p>2. 以及《Pull Request工作流》<a href="https://link.zhihu.com/?target=https%3A//github.com/oldratlee/translations/blob/master/git-workflows-and-tutorials/pull-request.md" class=" wrap external" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">oldratlee/translations/git-workflows-and-tutorials/pull-request.md</a></p><figure data-size="normal"><noscript><img src="https://pic1.zhimg.com/50/v2-608b2c0e6bc3123adeb7c0f9a943601b_hd.jpg?source=1940ef5c" data-caption="" data-size="normal" data-rawwidth="291" data-rawheight="203" data-default-watermark-src="https://pic1.zhimg.com/50/v2-80f01bca4efabb3359f37d1c6c099234_hd.jpg?source=1940ef5c" class="content_image" width="291"/></noscript><img src="https://pic1.zhimg.com/80/v2-608b2c0e6bc3123adeb7c0f9a943601b_720w.jpg?source=1940ef5c" data-caption="" data-size="normal" data-rawwidth="291" data-rawheight="203" data-default-watermark-src="https://pic1.zhimg.com/50/v2-80f01bca4efabb3359f37d1c6c099234_hd.jpg?source=1940ef5c" class="content_image lazy" width="291" data-actualsrc="https://pic1.zhimg.com/50/v2-608b2c0e6bc3123adeb7c0f9a943601b_hd.jpg?source=1940ef5c" data-lazy-status="ok"></figure><p>3. 各个相关的典型工作流的体系综述 参见：《Git工作流指南》  </p><a target="_blank" href="https://link.zhihu.com/?target=https%3A//github.com/oldratlee/translations/blob/master/git-workflows-and-tutorials/README.md" data-draft-node="block" data-draft-type="link-card" data-image="https://pic3.zhimg.com/v2-e72cb9c95a3deb6ca605636ba283a2ba_ipico.jpg" data-image-width="256" data-image-height="256" class="LinkCard old LinkCard--hasImage" data-za-detail-view-id="172"><span class="LinkCard-backdrop" style="background-image:url(https://pic3.zhimg.com/v2-e72cb9c95a3deb6ca605636ba283a2ba_ipico.jpg)"></span><span class="LinkCard-content"><span class="LinkCard-text"><span class="LinkCard-title" data-text="true">github.com/oldratlee/translations/git-workflows-and-tutorials/README.md</span><span class="LinkCard-meta"><span style="display:inline-flex;align-items:center">​<svg class="Zi Zi--InsertLink" fill="currentColor" viewBox="0 0 24 24" width="17" height="17"><path d="M13.414 4.222a4.5 4.5 0 1 1 6.364 6.364l-3.005 3.005a.5.5 0 0 1-.707 0l-.707-.707a.5.5 0 0 1 0-.707l3.005-3.005a2.5 2.5 0 1 0-3.536-3.536l-3.005 3.005a.5.5 0 0 1-.707 0l-.707-.707a.5.5 0 0 1 0-.707l3.005-3.005zm-6.187 6.187a.5.5 0 0 1 .638-.058l.07.058.706.707a.5.5 0 0 1 .058.638l-.058.07-3.005 3.004a2.5 2.5 0 0 0 3.405 3.658l.13-.122 3.006-3.005a.5.5 0 0 1 .638-.058l.069.058.707.707a.5.5 0 0 1 .058.638l-.058.069-3.005 3.005a4.5 4.5 0 0 1-6.524-6.196l.16-.168 3.005-3.005zm8.132-3.182a.25.25 0 0 1 .353 0l1.061 1.06a.25.25 0 0 1 0 .354l-8.132 8.132a.25.25 0 0 1-.353 0l-1.061-1.06a.25.25 0 0 1 0-.354l8.132-8.132z"></path></svg></span>github.com</span></span><span class="LinkCard-imageCell"><img class="LinkCard-image LinkCard-image--square" alt="图标" src="https://pic3.zhimg.com/v2-e72cb9c95a3deb6ca605636ba283a2ba_ipico.jpg"></span></span></a><p class="ztext-empty-paragraph"><br></p><p>--- 分 --- 割 --- 线 ---<br></p><p>展开来说明，如下：</p><p class="ztext-empty-paragraph"><br></p><p><b>1. 先简单地说说一下词源 </b></p><p>以方便从常见简单的意思 理解到 引申比喻的意思～</p><p>Fork 的本义是  <b>叉子</b>（名词）<b> 。</b></p><figure data-size="normal"><noscript><img src="https://pic2.zhimg.com/50/37c8a551c139e20502088d978d4529cd_hd.jpg?source=1940ef5c" data-caption="" data-size="normal" data-rawwidth="500" data-rawheight="103" class="origin_image zh-lightbox-thumb" width="500" data-original="https://pic3.zhimg.com/37c8a551c139e20502088d978d4529cd_r.jpg?source=1940ef5c"/></noscript><img src="https://pic2.zhimg.com/80/37c8a551c139e20502088d978d4529cd_720w.jpg?source=1940ef5c" data-caption="" data-size="normal" data-rawwidth="500" data-rawheight="103" class="origin_image zh-lightbox-thumb lazy" width="500" data-original="https://pic3.zhimg.com/37c8a551c139e20502088d978d4529cd_r.jpg?source=1940ef5c" data-actualsrc="https://pic2.zhimg.com/50/37c8a551c139e20502088d978d4529cd_hd.jpg?source=1940ef5c" data-lazy-status="ok"></figure><p class="ztext-empty-paragraph"><br></p><p>比较自然的引申成 <b>分叉</b>（动词） ，就像上面叉子，从左到从右，一条线变成多条了。</p><p>更多 词含义参见 <a href="https://link.zhihu.com/?target=http%3A//dict.cn/fork" class=" wrap external" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">fork是什么意思_fork在线翻译</a>。</p><p class="ztext-empty-paragraph"><br></p><p><b>2. 在计算机领域中，Fork一词的使用</b></p><p><b>2.1 Git/GitHub仓库克隆</b> </p><p>Git/GitHub 用户下面的图 来表达 Fork：分叉、克隆 出一个（仓库的）新拷贝。</p><figure data-size="normal"><noscript><img src="https://pic2.zhimg.com/50/3c13b2d3ddbf178b4debfea57644e520_hd.jpg?source=1940ef5c" data-caption="" data-size="normal" data-rawwidth="256" data-rawheight="256" class="content_image" width="256"/></noscript><img src="https://pic2.zhimg.com/80/3c13b2d3ddbf178b4debfea57644e520_720w.jpg?source=1940ef5c" data-caption="" data-size="normal" data-rawwidth="256" data-rawheight="256" class="content_image lazy" width="256" data-actualsrc="https://pic2.zhimg.com/50/3c13b2d3ddbf178b4debfea57644e520_hd.jpg?source=1940ef5c" data-lazy-status="ok"></figure><p>要了解GitHub中Fork的话 ，如 @<a href="http://www.zhihu.com/people/li-yu-ze-14" class="internal" data-za-detail-view-id="1043">李雨泽</a> 回答中所说的，其实是要理解的是 forking 工作流，参见本人的中文译文《Forking工作流》 <a href="https://link.zhihu.com/?target=https%3A//github.com/oldratlee/translations/blob/master/git-workflows-and-tutorials/workflow-forking.md" class=" wrap external" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">github.com/oldratlee/translations/git-workflows-and-tutorials/workflow-forking.md</a>，以及相关的典型工作流 《Git工作流指南》  <a href="https://link.zhihu.com/?target=https%3A//github.com/oldratlee/translations/blob/master/git-workflows-and-tutorials/README.md" class=" wrap external" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">oldratlee/translations</a></p><p><b>2.2 Linux 的 Fork 函数</b></p><p>运行着的程序分成2个（几乎）完全一样的进程，每个进程都启动一个从代码的同一位置开始执行的线程，这两个进程中的线程继续执行，就像是两个用户同时启动了该应用程序的两个副本。<br># 详见 <a href="https://link.zhihu.com/?target=http%3A//baike.baidu.com/item/fork" class=" wrap external" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">fork_百度百科</a></p><p>Fork 函数的命名所表达含义/比喻 和 GitHub中Fork 类似。<br>可见，Fork一词在计算机界 这样的用法 也是 <b>由来已久</b>。<br># Fork 函数 具体命名出现的时间 还没有考证，欢迎 Linux高手给出考证。</p><p><b>3. 为什么Fork会火起来（ 有些和楼主本义无关的闲话 :）</b></p><p>在『码农』圈 Fork一词，现在确实很火，当然和『全球最大的同性交友网站的GitHub』流行而大大提高出镜率有关系，常常可以看到『Fork me』这个词，鼓励别人Fork自己的仓库，通过PullRequest给自己的仓库做贡献，也是提高了自己仓库的知名度。<br># 关于 PullRequest 参见 <a href="https://link.zhihu.com/?target=https%3A//github.com/oldratlee/translations/blob/master/git-workflows-and-tutorials/pull-request.md" class=" wrap external" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">github.com/oldratlee/translations/git-workflows-and-tutorials/pull-request.md</a></p><p>另外，个人觉得的原因是：</p><p>1. Fork 一词 谐音了 『F*ck』，『Fork(F*ck) me』能体现自己的幽默态度。有<b>Sex</b>暗示的内容总是容易让人兴奋和记住，人的本性，哈哈</p><p>2. Fork可能也有那方面的含义：Forking - A sexual act.<br>参见 Yahoo Answer（Yahoo这个服务现在已经关停了...） <a href="https://link.zhihu.com/?target=https%3A//answers.yahoo.com/question/index%3Fqid%3D20080812235131AAlzJmn" class=" external" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043"><span class="invisible">https://</span><span class="visible">answers.yahoo.com/quest</span><span class="invisible">ion/index?qid=20080812235131AAlzJmn</span><span class="ellipsis"></span></a></p></span></div><div><div class="ContentItem-time"><a target="_blank" href="//www.zhihu.com/question/20431718/answer/74250205"><span data-tooltip="发布于 2015-11-27 22:27">编辑于 05-06</span></a></div></div><div><div class="ContentItem-actions Sticky RichContent-actions is-fixed is-bottom" style="width: 694px; bottom: 0px; left: 16px;"><span><button aria-label="赞同 336 " type="button" class="Button VoteButton VoteButton--up"><span style="display: inline-flex; align-items: center;">​<svg class="Zi Zi--TriangleUp VoteButton-TriangleUp" fill="currentColor" viewBox="0 0 24 24" width="10" height="10"><path d="M2 18.242c0-.326.088-.532.237-.896l7.98-13.203C10.572 3.57 11.086 3 12 3c.915 0 1.429.571 1.784 1.143l7.98 13.203c.15.364.236.57.236.896 0 1.386-.875 1.9-1.955 1.9H3.955c-1.08 0-1.955-.517-1.955-1.9z" fill-rule="evenodd"></path></svg></span>赞同 336</button><button aria-label="反对" type="button" class="Button VoteButton VoteButton--down"><span style="display: inline-flex; align-items: center;">​<svg class="Zi Zi--TriangleDown" fill="currentColor" viewBox="0 0 24 24" width="10" height="10"><path d="M20.044 3H3.956C2.876 3 2 3.517 2 4.9c0 .326.087.533.236.896L10.216 19c.355.571.87 1.143 1.784 1.143s1.429-.572 1.784-1.143l7.98-13.204c.149-.363.236-.57.236-.896 0-1.386-.876-1.9-1.956-1.9z" fill-rule="evenodd"></path></svg></span></button></span><button type="button" class="Button ContentItem-action Button--plain Button--withIcon Button--withLabel"><span style="display: inline-flex; align-items: center;">​<svg class="Zi Zi--Comment Button-zi" fill="currentColor" viewBox="0 0 24 24" width="1.2em" height="1.2em"><path d="M10.241 19.313a.97.97 0 0 0-.77.2 7.908 7.908 0 0 1-3.772 1.482.409.409 0 0 1-.38-.637 5.825 5.825 0 0 0 1.11-2.237.605.605 0 0 0-.227-.59A7.935 7.935 0 0 1 3 11.25C3 6.7 7.03 3 12 3s9 3.7 9 8.25-4.373 9.108-10.759 8.063z" fill-rule="evenodd"></path></svg></span>24 条评论</button><div class="Popover ShareMenu ContentItem-action"><div class="ShareMenu-toggler" id="Popover25-toggle" aria-haspopup="true" aria-expanded="false" aria-owns="Popover25-content"><button type="button" class="Button Button--plain Button--withIcon Button--withLabel"><span style="display: inline-flex; align-items: center;">​<svg class="Zi Zi--Share Button-zi" fill="currentColor" viewBox="0 0 24 24" width="1.2em" height="1.2em"><path d="M2.931 7.89c-1.067.24-1.275 1.669-.318 2.207l5.277 2.908 8.168-4.776c.25-.127.477.198.273.39L9.05 14.66l.927 5.953c.18 1.084 1.593 1.376 2.182.456l9.644-15.242c.584-.892-.212-2.029-1.234-1.796L2.93 7.89z" fill-rule="evenodd"></path></svg></span>分享</button></div></div><button type="button" class="Button ContentItem-action Button--plain Button--withIcon Button--withLabel"><span style="display: inline-flex; align-items: center;">​<svg class="Zi Zi--Star Button-zi" fill="currentColor" viewBox="0 0 24 24" width="1.2em" height="1.2em"><path d="M5.515 19.64l.918-5.355-3.89-3.792c-.926-.902-.639-1.784.64-1.97L8.56 7.74l2.404-4.871c.572-1.16 1.5-1.16 2.072 0L15.44 7.74l5.377.782c1.28.186 1.566 1.068.64 1.97l-3.89 3.793.918 5.354c.219 1.274-.532 1.82-1.676 1.218L12 18.33l-4.808 2.528c-1.145.602-1.896.056-1.677-1.218z" fill-rule="evenodd"></path></svg></span>收藏</button><button type="button" class="Button ContentItem-action Button--plain Button--withIcon Button--withLabel"><span style="display: inline-flex; align-items: center;">​<svg class="Zi Zi--Heart Button-zi" fill="currentColor" viewBox="0 0 24 24" width="1.2em" height="1.2em"><path d="M2 8.437C2 5.505 4.294 3.094 7.207 3 9.243 3 11.092 4.19 12 6c.823-1.758 2.649-3 4.651-3C19.545 3 22 5.507 22 8.432 22 16.24 13.842 21 12 21 10.158 21 2 16.24 2 8.437z" fill-rule="evenodd"></path></svg></span>喜欢</button><button data-zop-retract-question="true" type="button" class="Button ContentItem-action ContentItem-rightButton Button--plain"><span class="RichContent-collapsedText">收起</span><span style="display: inline-flex; align-items: center;">​<svg class="Zi Zi--ArrowDown ContentItem-arrowIcon is-active" fill="currentColor" viewBox="0 0 24 24" width="24" height="24"><path d="M12 13L8.285 9.218a.758.758 0 0 0-1.064 0 .738.738 0 0 0 0 1.052l4.249 4.512a.758.758 0 0 0 1.064 0l4.246-4.512a.738.738 0 0 0 0-1.052.757.757 0 0 0-1.063 0L12.002 13z" fill-rule="evenodd"></path></svg></span></button></div><div class="Sticky--holder" style="position: static; inset: auto; display: flex; float: none; margin: 0px -20px -10px; height: 54px; width: 694px;"></div></div></div><div class="ModalWrap"><div><div class=""></div><div class="ModalExp-content"><div class="ModalWrap-content"><div class="ModalWrap-title">继续浏览内容</div><div class="ModalWrap-item"><div class="ModalWrap-itemImg"><img src="https://pic4.zhimg.com/80/v2-88158afcff1e7f4b8b00a1ba81171b61_720w.png" alt=""></div><div class="ModalWrap-itemContent"><div class="ModalWrap-itemTitle">知乎</div><div class="ModalWrap-itemDesc">发现更大的世界</div></div><div class="ModalWrap-itemBtn">打开</div></div><div class="ModalWrap-item"><div class="ModalWrap-itemImg"><img src="https://picb.zhimg.com/80/v2-a448b133c0201b59631ccfa93cb650f3_1440w.png" alt=""></div><div class="ModalWrap-itemContent"><div class="ModalWrap-itemTitle">Chrome</div></div><div class="ModalWrap-itemBtn">继续</div></div></div></div></div></div><div><div><div class=""></div><div class="ModalLoading-content"><svg width="30" height="30" viewBox="0 0 66 66" xmlns="http://www.w3.org/2000/svg" class="CircleLoadingBar" aria-hidden="true"><g><circle class="path" fill="none" stroke-width="6" stroke-linecap="round" cx="33" cy="33" r="30"></circle></g></svg></div></div></div></div>