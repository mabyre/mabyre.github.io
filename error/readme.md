# Jekyll is on error

Why use Jekyll ? Is the question I'm asking me now for days.

Ok now we have a usable way to navigate into site but this is by hand. Every support should be carry from Jekyll just don't work.

The misunderstanding with Jekyll came from the documentation, it's to hard at the begining with complex requirements like Installation with Ruby, RubyGems, GCC, Make and red message like :

> If you are using Ruby version 3.0.0 or higher, step 5 may fail. You may fix it by adding webrick to your dependencies: bundle add webrick

**You don't need all that !!!**

If you use Jekyll within GitHub Pages all this is installed and correctly configured. So you can jump into the documentation:

[Jekyll Docs](https://jekyllrb.com/docs/)

directly to **Pages** and **Posts**.

I am a very experienced developer and starting with Jekyll and GitHub Pages I was amazed by the complexity of this doc just to make a few html pages it was repulsive.

On one hand you have GitHub Pages that leaves you with Jekyll and in the other hand you have Jekyll that restart from the begining.

# Display an image with jekyll

<img style="margin: 10px" src="https://github.com/mabyre/mabyre.github.io/blob/master/images/error/2022-07-21_15h36_12.png" alt="Github Pages Settings" />

To get the Build :

<img style="margin: 10px" src="https://github.com/mabyre/docs/blob/master/images/2022-12-19_15h19_55.png" alt="Access to build" />

## Error 1

<img style="margin: 10px" src="https://github.com/mabyre/docs/blob/master/images/2022-07-21_15h36_12.png" alt="Error" />

## Error 2

Jekyll try to display an image

[Error while building](/images/error/2022-07-21_15h36_12.png)

(/images/error/2022-07-21_15h36_12.png)

</images/error/2022-07-21_15h36_12.png>

![Error while building](/images/error/2022-07-21_15h36_12.png)

## Error 3

Here you can see the famous message :

> To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
> Conversion error: Jekyll::Converters::Scss encountered an error while converting 'assets/css/style.scss':
> No such file or directory @ dir_chdir - /github/workspace/docs

With no solution at all

![Error while building](/images/error/2022-07-21_16h02_29.png)

## Error 4

If you can't see your Jekyll site go to "Actions" tab.

![Error while building](/images/error/2022-12-19_15h19_55.png)

## No Error

What you should see, is something like this :

![Error while building](/images/error/2022-12-22_15h58_45.png)

Following by this while the process ending well :

![Error while building](/images/error/2022-12-22_15h52_06.png)

---
[home](../home)