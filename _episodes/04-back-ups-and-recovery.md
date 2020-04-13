---
title: "Back-ups and recovery"
teaching: 25
exercises: 50
questions:
- "Why are automated backups important?"
- "How do I make a backup plan?"
objectives:
- "Learn who to ask for help"
- "Know what the back up systems are"
keypoints:
- "Automated backups can reduce the time and money costs of things going badly."
- "A backup plan should be in response to your data's sensitivity and difficulty of collection. It should address risks and mitigations of those risks. It should cost less than being hit by the thing you are defending against. "
---


> ## The first rule of backups
>
> It is not a backup until you have restored from it.
-- Brian Ballsun-Stanton


# What is a sync client?

A sync client is, "[A] continuous file synchronization program. It synchronizes files between two or more computers in real time..." (Syncthing 2020)[https://syncthing.net/]

* Keeps a local and remote copy up to date
* Designed for easy migration between computers, (i.e. work and home)
* Always on, presumes internet
* Does not provide versioning to a reliable level.

# What is a Backup client?

* Not designed to share data
* **No risk of "overwriting" local data accidentally.**
* Can capture all files, or the latest changes in files
* Keeps controllable versions with a specific retention policy. (Are there legal lengths which must be obeyed? Are there risks for keeping longer?)
* Designed to run automatically, but not continously.    
* If a cloud service, encrypts your data such that they cannot access it?

> ## Challenge: Common clients (10 minutes)
> 
> Add comments in the shared document.
>
> 1. Is Dropbox a backup client?
>
> > ## Solution
> >
> > No. It can overwrite your local files, shares file data at its discretion to "Dropbox uses certain trusted third parties (for example, providers of customer support and IT services) to help us provide, improve, protect, and promote our Services." (Wired)[https://www.wired.com/story/dropbox-sharing-data-study-ethics/], is not liable for data loss, and saves versions up to 30 days only.
> {: .solution}
>
> 2. Is OneDrive a backup client?
>
> > ## Solution
> > 
> > This is a trick question. The [OneDrive sync client](https://support.office.com/en-us/article/choose-which-onedrive-folders-to-sync-to-your-computer-98b8b011-8b94-419b-aa95-a14ff2415e85) is *not* a backup, because it can overwrite local files on your computer. While Micrsoft advertises OneDrive as a backup client, with the [backup your folders](https://support.office.com/en-us/article/back-up-your-documents-pictures-and-desktop-folders-with-onedrive-d61a7930-a6fb-4b95-b28a-6552e77c3057) option, it looks like this option is syncing, rather than creating backups (See [backblaze's discussion of differences](https://www.backblaze.com/blog/cloud-backup-vs-cloud-sync/) and the discussion inside [microsoft's answers site](https://answers.microsoft.com/en-us/msoffice/forum/all/onedrive-backup-vs-onedrive-sync/27794e15-3507-47e8-b469-30fe9c88693b). But you only have 3-30 days to recover deleted files in standard accounts, which makes this **not a backup**. 
> 
{: .challenge}

Sync clients and backup clients solve different problems, and with some care, there's no problem running both.


> ## The 3-2-1 Rule
>
> When storing data, follow the 3-2-1 rule:
>
> Keep *3* copies of your files in *2* different locations, with *1* copy in a location in another geographic area
>
> Master copy: Keep at secure location
>
> Working copy: Keep on a reliable/safe device or locations
>
> Back up copy: Keep off-site
> 
> [11 ways to avert a data-storage disaster
](https://www.nature.com/articles/d41586-019-01040-w)
{: .callout}


> ## Challenge - Why have a 3-2-1 strategy? (10 minutes)
>
> What could possibly go wrong? Write your answers in the shared document.
{: .challenge}

# How to make a backup plan


1. What do you want to protect? Where is it? 
2. Articulate risks
    * Examples:
        * [Who is harmed if the data be left at the train station?](https://www.theguardian.com/politics/2008/jun/12/defence.terrorism)
        * [Do you need to keep the data in case of ethics investigation or as per NSW law?](https://www.records.nsw.gov.au/recordkeeping/education%3A-higher-and-further-education-records-%28ga47%29) (Section 3.5.1)
        * [What happens if the data vanishes in a fire?](https://thesiswhisperer.com/2011/10/27/back-it-up/)
    * Formally:
        * What is the cost of replacing all or part of the data?
        * What is the cost of a data breach?
        * Where is the data stored and what can happen at each place where the data lives?
    * Multiply the cost of the above by the odds of failure.
        * [1-3% a year for a hard drive failing](https://www.backblaze.com/blog/backblaze-hard-drive-stats-q3-2019/)
        * Odds of fire, workplace theft, etc. (This rabbit hole can go as deep as you like.) [Mean fire experience probability](https://www.iafss.org/publications/aofst/7/85/view/aofst_7-85.pdf) says "The mean annual probability of having a fire experience whilst an adult was .0125." 
    * Your budget for your backups should be lower than the odds of the thing occuring times the cost of fixing it. 
3.  Find automatic services for your 3-2-1 strategy
    * The more you have to do manually, the less the odds of a backup being performed during stressful or busy times.
    * Most important backup is the offsite backup. Find a service or program that can offer versions and deleted files out to the entire history of your backup. Make sure it runs automatically on all of your computers.
    * Backups' backup, in case your online account is compromised is your local backup. Figure out what high-relability media you will be using (a USB flash drive is not reliable, external hard disks are adequate for the purpose) and how you can semi-automate backups. 
4.  Figure out your test strategy.
    * [Backups which haven't been tested are not backups](https://thedailywtf.com/articles/the-backup-pipeline)
    * [No, really](https://www.independent.co.uk/arts-entertainment/films/news/pixars-billion-dollar-delete-button-nearly-lost-toy-story-2-animation-7758083.html)
    * Restoring from a historical version of your backups: "I want last tuesday's version of this document" is a great way to know that the entire system is working.
5.  Document what you need to do to backup and to restore data, using a checklist. Assume you will be panicked and not remembering anything when you really need to restore data.


> ## Challenge - Backup Plan (30 minutes)
>
Group: Make, document, and share a backup plan. Use a variety of resources and share those too.
> Think, pair, share
{: .challenge}
