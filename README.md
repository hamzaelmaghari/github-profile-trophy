# Github Profile Trophy

[![Github issues](https://img.shields.io/github/issues/ryo-ma/github-profile-trophy)](https://github.com/ryo-ma/github-profile-trophy/issues)
[![Github forks](https://img.shields.io/github/forks/ryo-ma/github-profile-trophy)](https://github.com/ryo-ma/github-profile-trophy/network/members)
[![Github stars](https://img.shields.io/github/stars/ryo-ma/github-profile-trophy)](https://github.com/ryo-ma/github-profile-trophy/stargazers)
[![Github license](https://img.shields.io/github/license/ryo-ma/github-profile-trophy)](https://github.com/ryo-ma/github-profile-trophy/)

🏆 Add dynamically generated GitHub Trophy on your readme

# Demo

<img width="667" src="https://user-images.githubusercontent.com/6661165/91206530-4766d200-e742-11ea-961a-253e9f84c1c0.png">


# Quick Start

Add following code to your readme.  
Change the `?username=` value to your GitHub's username.

```
[![trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma)](https://github.com/ryo-ma/github-profile-trophy)
```

# Optional Request Parameters

* [title](#filter-by-titles)
* [rank](#filter-by-ranks)
* [column](#specify-the-maximum-row--column-size)
* [row](#specify-the-maximum-row--column-size)

## Filter by titles

You can filter the display by specifying the titles of trophy.  

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&title=Follower
```

<img width="110" src="https://user-images.githubusercontent.com/6661165/91331077-45197c00-e805-11ea-85fc-37785abee37c.png">

If You want to specify multiple titles.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&title=Star&title=Follower
```

## Filter by ranks

You can filter the display by specifying the ranks.  
`Available values: SSS SS S AAA AA A B C`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=S
```

<img width="110" src="https://user-images.githubusercontent.com/6661165/91327681-d20e0680-e800-11ea-8b59-bdd6a64076a2.png">

If You want to specify multiple ranks.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=S&rank=AAA
```


## Specify the maximum row & column size

You can specify the maximum row and column size.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&row=2&column=2
```

<img width="220" src="https://user-images.githubusercontent.com/6661165/91328030-48126d80-e801-11ea-8547-d2633de85b75.png">