# EGPD2022
This is the website for the annual European Geothermal PhD Days conference of 2022.

# Building the website for future EGPDs

Follow these steps to create the website:

1. Create a new public repository on Github.
2. Click on import repository.
3. Enter the URL: `https://github.com/davidn182/EGPD2022.git`
4. Fill in a repository name, such as "egpd2023".
5. Select "Public" for visibility.
6. Create the repository.
7. Open the repository and navigate to "Settings" → "Pages".
8. Choose the branch as "main".
9. Click "Save"
10. Now you can find your website at `https://your-username.github.io/(name of your repo)`.
11. If you don't want the website to have the github.io extension you can go to "Settings"-> "Pages"->"Custom domain" and select the domain in which you want to host the repository.
Keep in mind that you'll need to purchase the domain from a domain registrar. For example, we purchased ours with [google domains](https://domains.google/).
12. If you purchase a domain called `www.egpd2023.com` you will have to add a file in your repo called `CNAME` and add the following lines:
```CNAME
egpd2023.com
www.egpd2023.com
```

That's it! You've successfully created and configured your website for the future EGPDs.
