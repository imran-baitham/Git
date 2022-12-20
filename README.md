<img src="https://git-scm.com/images/logo@2x.png" alt="imran baitham"/>
<h1>😍 Git</h1>
<p>( fast version control )</p>

<p>Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems.</p>

<img src="https://devconnected.com/wp-content/uploads/2019/12/featured-10.png" alt="imran baitham"/>

<h2>Git Init</h2>    
<pre><code class="text">git init</code></pre>

<h2>Git Clone</h2>    
<pre><code class="text">git clone branch-name</code></pre>
<p>“git clone” command and specify the copied URL to clone the selected Git repository.</p>

<h2>Fetch all branchs</h2>    
<pre><code class="text"> git fetch --all</code></pre>
<p>we have used the “–all” flag which will fetch all metadata of branches.</p>

<h2>List Remote Branches</h2>    
<p>To display all remote branches, execute the “git branch” command:</p>
<pre><code class="text"> git branch -r</code></pre>
<p>In the above-mentioned command, the “-r” indicates the remote branches. As you can see, currently, we have three branches in the remote repository</p>

<h2>pull --all</h2>    
<pre><code class="text">git pull --all</code></pre>
<p>shows that all remote branches are successfully pulled</p>

<h2>1. Create Git branch using checkout</h2>    
<pre><code class="text">git checkout -b branch-name</code></pre>

<b>Example</b>

<pre><code class="text">git checkout -b feature<br/>
Switched to new branch 'feature'</code></pre>

<p>⭕️ You can inspect existing branches by running the “git branch” command with the “-a” option for all branches.</p>
<pre><code class="text">git branch -a</code></pre>

<p>⭕️ To get commits SHA from your history, you have to use the “git log” with the “–oneline” option.</p>
<pre><code class="text">git log --oneline --graph</code></pre>

<!-- ===================================================== -->

<h2>Git Delete Branch</h2>
<pre><code class="text">git branch --delete branchname</code></pre>

<h2>The default branch has been renamed!</h2>
<p>master is now named develop<br/>
If you have a local clone, you can update it by running the following commands.</p>

<pre><code class="text">git branch --delete branchname</code></pre>
