# Maven + GitHub Demo

A simple Java Maven project with a GitHub Actions CI workflow.

## Run locally

```bash
mvn clean package
```

Run the application:

```bash
java -cp target/classes com.example.App
```

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial Maven project"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

After pushing, open the GitHub repository and select **Actions** to see the Maven build.
