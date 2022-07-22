<h1>😍 Git </h1><p>( fast version control )</p>

<p>Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems.</p>

<img src="https://devconnected.com/wp-content/uploads/2019/12/featured-10.png" alt="imran baitham"/>

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

<!-- <h2>Git Delete Branch</h2>
<pre><code class="text">git branch --delete branchname</code></pre> -->
