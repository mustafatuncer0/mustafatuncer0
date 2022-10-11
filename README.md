- 👋 Hi, I’m @mustafatuncer0
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
mustafatuncer0/mustafatuncer0 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

## Contents

<details>
<summary><strong>Details</strong></summary>

-   [Start Up](#start-up)


</details>


# Start Up

All services can be initialised from the command-line by running the
[services](https://github.com/FIWARE/tutorials.Entity-Relationships/blob/NGSI-v2/services) Bash script provided within
the repository. Please clone the repository and create the necessary images by running the commands as shown:

```console
git clone https://github.com/FIWARE/tutorials.Entity-Relationships.git
cd tutorials.Entity-Relationships
git checkout NGSI-v2

./services start
```

This command will also import seed data from the previous
[Store Finder tutorial](https://github.com/FIWARE/tutorials.Getting-Started) on startup.

> :information_source: **Note:** If you want to clean up and start over again you can do so with the following command:
>
> ```console
> ./services stop
> ```


