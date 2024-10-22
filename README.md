# Create your own blog now!

Your blog will be generated by [marmite](https://rochacbruno.github.io/marmite/)

<details>

<summary> Click to see screenshots </summary>

**Light Mode**
![index-light](https://github.com/user-attachments/assets/ebb177a3-5c28-437f-88d2-2400474dd84c)
![post-light](https://github.com/user-attachments/assets/c4ea0485-efee-438a-82d1-1c8d9b31a3e8)

**Dark Mode**
![index-dark](https://github.com/user-attachments/assets/c72a9216-e553-4d91-b48e-7b1e913b264f)
![post-dark](https://github.com/user-attachments/assets/61e6aad9-d84d-4e12-9737-ece02ffd39d2)

</details>

---

## Step 1

[CLICK ON FORK BUTTON](https://github.com/rochacbruno/make-me-a-blog/fork) and name your fork `blog`.

## Step 2

Access https://github.com/YOURUSER/REPONAME/settings/pages and set the
pages source to **Github Actions**

## Step 3

Then edit the `marmite.yaml` with your own information. (IMPORTANT! change the `url:..` field to match your own repo)

## Step 4

Commit and see the Github Actions building a blog for you.

Your blog will be published at https://YOURUSER.github.io/blog

You can add add [custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site) later

---

## Building locally

```console
$ git clone git@github.com:YOURUSER/blog.git
$ cd blog
```

```console
$ cargo install marmite
```

```console
$ marmite . site
Site generated at: /site/
```

Learn more on [marmite](https://rochacbruno.github.io/marmite/)

