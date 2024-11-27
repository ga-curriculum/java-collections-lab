<h1>
  <span class="headline">Java Collections Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Setup

Open your Terminal application and navigate to your <code class="filepath">~/code/ga/labs</code> directory.

```bash
cd ~/code/ga/labs
```

Clone the [Java Collections Lab starter code](https://git.generalassemb.ly/modular-curriculum-all-courses/java-collections-lab-starter) repository.

Clone a copy of your remote repo locally by using the `git clone` command:

```bash
git clone https://git.generalassemb.ly/modular-curriculum-all-courses/java-collections-lab-starter.git java-collections-lab
```

> 💡 The `java-collections-lab` at the end of this command will place the contents of the `java-collections-lab-starter` repo into a directory named <code class="filepath">java-collections-lab</code>.

Next, `cd` into the newly created directory:

```bash
cd java-collections-lab
```

You don't want GA commits on your work, so remove the existing Git information from this starter code:

```bash
rm -rf .git
```

To get this work to GitHub, initialize a new Git repository:

```bash
git init
git add .
git commit -m "initial commit"
```

Make a new repository on your personal GitHub account named `java-collections-lab`.

Link your local work to your remote GitHub repo:

```bash
git remote add origin https://github.com/<github-username>/java-collections-lab.git
git push origin main
```

<blockquote class="warning">
  🚨 Do not copy the above command. It will not work. Your GitHub username will replace <code>&lt;github-username&gt;</code> (including the <code><</code> and <code>></code>) in the URL above.
</blockquote>

Open IntelliJ IDEA Community Edition and open the project by selecting the **Open** option on the launch screen.

Next, navigate to the `java-collections-lab` directory you just created and open the project.

Trust the project if you are prompted.

## Running the Tests

This lab includes a set of tests to help you verify your work. To run the tests, right-click on the <code class="filepath">src/test/java</code> directory and select **Run 'All Tests'**.
