# Investigating texts with Voyant

Voyant is a web-based tool for text analysis that is designed to combine ease of use with a sophisticated array of visualization methods. My general classroom experience has been that students are intrigued by it, but pretty skeptical of how much Voyant can actually tell them about a text. That's good, I think! I like to use Voyant to probe how texts come to be meaningful. If word frequencies aren't sufficient, how *do* we find patterns in texts? Is close reading possible with a very large corpus of texts? If we can't hold all those texts in our heads, then what *would* help us find patterns in texts? Is the answer some tool that hasn't been invented yet? Or is the entire experiment doomed to failure? 

I find these questions especially useful in opening discussion between students who have experience studying literature and students from other fields, since they often expose some different assumptions about how we can divine the "truth" about texts. I hardly need mention that I wouldn't suggest to students that Voyant (or text analysis in general) offers a straightforward window into a text. Instead, I prefer to use it as a way to talk about how we interact with texts and what kind of meaning evades capture by computational tools.

I wouldn't, of course, front-load an exploration of Voyant with all of this baggage. Instead, I'd ask students to investigate texts with it (as I demonstrate below) and then, in discussions afterward, prompt them to consider some of these questions — and add their own!

Now that we've dispensed with that preface, I'll explain that in order to visualize texts with Voyant, you'll first need to get documents into it and next (the more complicated part) try to make sense of the visualizations Voyant produces.

## 1. Download our corpus

I'd like you to begin by downloading a couple of files. One contains a corpus of nineteenth-century children's books; the second is simply a list of the books contained in the corpus.

Point your browser to [https://www.dropbox.com/s/f7z1i8hg9pzg9wk/American.zip?dl=1.](https://www.dropbox.com/s/f7z1i8hg9pzg9wk/American.zip?dl=0) A download of a zip file should begin immediately. Once the zip file downloads, figure out where it went (and try to remember that for later!) and then double-click it to decompress the file. You should end up with a file called **American** that contains 33 text files.

Next, go to [https://www.dropbox.com/s/4sug61lqvfw3673/American.xlsx?dl=1](https://www.dropbox.com/s/4sug61lqvfw3673/American.xlsx?dl=0) to download the list of titles contained in the corpus. You don't have to do anything in particular with it; it's just for your information.

![][1]

[1]: images/investigating-texts-with-voyant/download-our-corpus.png

## 2. Open Voyant

Go to [https://voyant-tools.org/](https://voyant-tools.org/) to begin. I recommend opening Voyant in one browser window and keeping this tutorial open in a second. Arrange the two windows so that you can see them both at the same time. Once you've done that, you've mastered the hardest part of this tutorial!

Here, I'll pause to say a word or two about how to get texts in to Voyant. As the help text indicates, you can simply paste text into the window, or enter URLs (for example, to Project Gutenberg texts). If you click on the **Open** button, you'll see that Voyant offers a couple of corpora for demonstration purposes. Finally, you can **Upload** texts from your own computer. That's what we'll do in the next step.

![][2]

[2]: images/investigating-texts-with-voyant/open-voyant.png

## 3. Upload your texts

We'll now upload the texts we downloaded in **Step 1**. Click on the **Upload** button and navigate to the **American** folder you downloaded in the first step. Inside the folder, hold down the **shift** key to select all 33 of the texts. Then click **Open**. 

Voyant will take a few moments to load in your texts.

![][3]

[3]: images/investigating-texts-with-voyant/upload-your-texts.png

## 4. What the heck are we looking at? (1)

The Voyant interface can be a bit overwhelming. It consists of a set of panels, each of which provides a different view of your texts.

A few useful pieces of information about the Voyant interface: If you hover your cursor over the borders between panels, you'll see that you can make each panel larger or smaller. Each panel contains a question mark in the upper right-hand corner; hovering over it provides you with useful information about what you're looking at.

The panel labeled **Summary** may be the best place to start. You'll see that it offers some information about the entire corpus. If you click on the **Documents** tab, you'll find some basic statistics about each of the texts. **Phrases** lists some common phrases, as well as a tiny graph that shows where in the text they appear.

The **Cirrus** panel offers a word cloud, with more frequently occurring words shown in a larger size. Try clicking on one of the words. You'll see that some of the other panels update to show information about that word. **Terms** displays more or less the same information as a list. **Links** shows which words tend to appear in proximity to each other.

![][4]

[4]: images/investigating-texts-with-voyant/what-the-heck-are-we-looking-at---1-.png

## 5. What the heck are we looking at? (2)

To understand the tools the remaining panels offer, take a look at [Voyant's documentation](http://docs.voyant-tools.org/tools/), which is quite robust. 

You'll notice that the list of visualizations contains quite a number of tools that don't appear in the interface you're working with. That's because Voyant is designed to be customizable; you can swap visualization types in and out to suit your needs. This is probably more than you're interested in doing right now, but if this intrigues you, you can do that by clicking on the window icon that appears when you hover your cursor over the upper right-hand corner of each panel.

![][5]

[5]: images/investigating-texts-with-voyant/what-the-heck-are-we-looking-at---2-.png

## 6. Explore your texts!

Spend some time investigating the tools Voyant offers, paying particular attention to patterns and trends.

Can you discern significant differences among texts? In the progression of a single text? Do these differences seem meaningful? Do you trust the patterns suggested by the visualizations? Could you verify their accuracy somehow?

![][6]

[6]: images/investigating-texts-with-voyant/explore-your-texts-.png

## 7. Some final notes

Voyant has some nice features for sharing and embedding. If you hover your cursor over the upper right-hand corner of the main window, you'll find a square with an arrow in it. Clicking on this icon allows you to obtain a URL that links directly to the interface you're looking at, pre-loaded with your corpus. This can be very handy in a classroom setting!

Each panel in the Voyant interface contains a similar icon, meaning you can also link to or embed each visualization separately.

**Stopwords** are words that a tool ignores, on the logic that they aren't meaningful and may skew your results. Voyant automatically incorporates a list of stopwords, including **the, and, **and the like. To see and alter the stopwords Voyant uses, click on the **Define options for this tool** icon in each panel's upper right-hand corner.

![][7]

[7]: images/investigating-texts-with-voyant/some-final-notes.png