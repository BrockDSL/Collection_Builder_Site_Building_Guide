# Welcome!

Welcome to the Collection Builder Site Building Guide!  This guide will walk you through the steps required to build your very own basic Collection Builder site using GitHub pages.  In order to follow through this tutorial, you will need:

1. A GitHub account
2. Some content that you want to exhibit (jpeg's, pdf's, mp3 files, mp4 files, etc.)
3. Metadata for each of those items

Once you have your account and materials ready you can get started.

# Step 1 - Get your Git in Gear

The first step to building a Collection Builder site using GitHub pages is to clone all of the code that works behind the scenes to turn your metadata into an exhibit.  To do this, go to https://github.com/CollectionBuilder/collectionbuilder-gh.  You will see a repository containing all sorts files and folders that make up Collection Builder.  What you want to do is create a repository of your own and copy all of those files into it.  Luckily our friends on the Collection Builder team have made this very easy by turning their repository into a template that can be copied easily.

To copy the contents of the repository, click on the green "Use this template" button at the top.  Next, you will need to give a name to your repository.  This will determine what the URL for your Collection Builder Exhibit will be so make sure to pick something that makes sense for your project.  Once you have a good title, check that the bubble for "Public" is checked and then click the green "Create repository from template" button.

Just like that you now have your very own repository with all of the code needed to build a Collection Builder Exhibit!


# Step 2 - Make and Manage your Metadata

The next thing you need to do is prepare your content that will be displayed in your Collection Builder Exhibit.  The most important part of your entire site is the metadata csv file.  This is the file that Collection Builder will use to build all of the item pages, visualizations, and more.  The structure of the metadata file is very impotant as there are some fields that are absolutely required in order for your site to work.  The steps below will help you build a clean, functional metadata file.

1. Start by either creating your own csv file (In Excel, Google Sheets, etc) or by downloading the template from [HERE](https://brocku-my.sharepoint.com/:f:/g/personal/dbrett_brocku_ca/EpNSItFDGLNEmeV6FTtwC1UBiDJ_otCzUyVWZa4_9Emipw?e=0ROcBg).
2. Next you will decide what metadata fields you will include.  You can add as many fields as you want to your metadata file but there are four fields that you MUST include in order for Collection Builder to work.  They are: 
     - objectid (A unique identifier for each item that cannot contain space or special characters)
     - title (This is a descriptive name for the item)
     - format (This describes what type of media the item is using [MIME type standards](https://www.iana.org/assignments/media-types/media-types.xhtml). Some of the most commonly used fortmats are image/jpeg, application/pdf, audio/mp3, video/mp4)
     - filename (this is the name of the item that the metadata is for.  This field must match perfectly to the name of the file eg. demo1.jpg or analysis1.pdf and cannot contain special characters or spaces so make sure your filenames also adhere to this rule)
3. In addition to the four mandatory fields there are certain fields that need to be included if you want to use some of the most interesting functions of Collection builder.  Each of these functions represent a page on your collection builder site.
     - The Map Page.  In order to use the map page feature of Collection builder you will need to include fields for latitude and longitude in your metadata file.
     - The Timeline Page.  In order to use the timeline page feature of Collection Builder you will need to include a date field (date format can be yyyy, yyyy-mm, or yyyy-mm-dd)
     - The Subject Wordcloud page.  In order to use the subject wordcloud page feature of Collection Builder you will need to include a subject field.  Subjects can be anything you want and you can assign multiple subjects to an item by seperating them with a semicolon (;).
     - The Location Wordcloud Page .  In order to use the location wordcloud page feature of Collection Builder you will need to include a location field.
4. Feel free to add any other metadata fields that you think may be relevant (description, creator, language, etc) keeping in mind that field names must be in lowercase and not contain any characters other than letters and numbers (no spaces allowed!).
5. Fill in the information for all of your items and them save your file.  (Make sure not to leave any fields blank and that the name for your csv file does not include any spaces)
6. Now that you have a fully prepped metadata file to go along with all of the item you want to exhibit, you will need to get everything onto GitHub.
     - For the metadata file, you will go to the main page of your GitHub repository and click on the \_data folder










  
**This tutorial is brought to you by the Brock University Digital Scholarship Lab.  For more information on the DSL check out our website at [www.brocku.ca/library/dsl/](https://brocku.ca/library/dsl/) or you can e-mail us at dsl@brocku.ca.**  
  
You can also find us on:  
[Facebook](https://www.facebook.com/Brock-University-Digital-Scholarship-Lab-349407235866792/)  
[Twitter](https://twitter.com/brock_dsl)  
[Instagram](https://www.instagram.com/brock_dsl/?hl=en)  
[YouTube](https://www.youtube.com/channel/UC2eEqPkDo-1N3qilxv-N_1g/featured?view_as=subscriber)










<!--- Please use reference style images so that it is easier to update pictures later --->

[imglogo]: INSERT LOGO FILENAME HERE
