---
layout: post
title: "iOS Writing Bliss"
categories: [writing, tools]
---

I have absurd requirements when it comes to writing. A big part of this comes from the fact that I've been developing software for over a decade. I have certain habits, tools, and expectations for how my work should proceed. Let's detail out my... issues.

<!--more-->

## Git

I keep all my work versioned using Git. This is absolutely a requirement for anything I do. For those who don't know, Git is a system through which you "commit" changes (work you've done). Those changes are saved as a point in time, allowing you to restore your work to any commit.

There's a mental freedom in writing that Git affords you. Specifically, Git makes it easy to delete stuff you like. I can't count how many times I've written a wonderful scene that doesn't fit. I know it needs to go, but there was so much good stuff in there. With Git, I know I can always go back and find it, which makes it much less painful to delete. Without Git, I would have a much harder time deleting stuff.

## Vim

I've become addicted to a very specific way of entering text: Vim.

Most people won't know what Vim is. It hails from the days before GUI's (graphical user interfaces) when all text had to be manipulated using the keyboard alone. This is the realm of command prompts and text-only interfaces, where finger-dexterous wizards ply their craft using weird and obscure runic-like symbols sent spiraling into the black ether. In those days, we called it VI, but it has since then been iMproved... thus, Vim.

Vim operates in three modes: command, insertion, and selection.

In command mode, the keyboard performs commands instead of entering text: `j` moves the cursor down a line, `k` moves it up a line, `h` moves right, `l` moves left. `e` moves to the end of the word, and `w` moves to the beginning of the next word. I can delete a word with `daw` or delete a sentence with `das`. There are thousands of combinations.

In insertion mode, the keyboard does what most poeple think it should do: it enters text just like any text editor. To leave it for command mode, I press escape.

Selection mode: This is a special command mode that allows you to select visual blocks, or columns of text, then perform commands on each row of that text. I could, for instance, select several rows, press `i` to enter insertion mode, and then press ` - ` to prepend a dash to every selected row at once.

If Vim sounds absurdly complicated, that's because it is. It took me over a month to become vaguely proficient at it, and several months to get back to "normal operating" speed. Yet from there, I continued to improve as muscle memory allowed me to perform edits faster than I could ever have managed before.

It's hard for me to overstate just how efficient Vim has made me. In the time it takes you to reach for the mouse, I've already rearranged the sentence.

As a secondary bonus (but one of the primary driver for me), it's all but eliminated RSI (repeative stress injuries). With "normal" text editors, you're constantly "reaching" for the arrow keys, the mouse, or twisting your hand to copy/paste/etc. With Vim, that's all gone. All the commands I need are on the keyboard, no twisting required. 

## Cloud Sync

Technically, Git can be used for syncing but it's a manual process: you commit and push the changes to a server, then pull those changes on another computer. It works... but I can't count how many times I forgot to push changes, leaving me without my latest work on another device.

So I rely on a secondary syncing service to keep my changes in sync. For a long time this was Dropbox. I've moved away from that lately [^4], choosing to roll my own syncing server using NextCloud. In both cases, all the changes I make our automatically synced between machines.

## iOS

I've long had a love-hate relationship with iOS when it comes to writing. I've done significant portions of my writing on my iPhone and that is nothing short of amazing. I have vivid memories of writing stories with one hand while a sleeping baby rests in my arms. That would not be possible without the incredible app ecosystem iOS provides.

And yet... Git and cloud sync doesn't work together. I can have both, but not at the same time. There is a fantastic little app called "Working Copy", a full git client, that I can use to get, make, and push changes with. However, it did not sync with cloud providers like Dropbox, and it's text writing system (mostly geared toward coding) leaves much to be desired. There were _other_ apps I could use to write and some of them _did_ sync to cloud providers (Ulysses was my favorite), but I couldn't use them to push changes (save/commit my work).

Finally, there was the iPad. With a full keyboard, the iPad _should_ be a fantastic text editor. It should be, except for one tiny omission: there's no escape key.

There have been attempts to create a Vim editor in iOS. For the most part these have worked except for the damn escape key. It is, simply put, a foundational part of Vim. 

On my Mac, I long ago remapped the Caps Lock key to Escape, allowing me to transition to command mode easily and with the least strain to my wrist as possible. With no Escape key on an iOS keyboard (and no way to even send an escape command), the editors always had to resort to some other means: an on screen escape key, or customizable key combo like ctrl+c. Sure, it works, but Vim is all about muscle memory and my text was littered with capitalized nonsense as I habitually used what now comes natural.

So, I gave up.

## Bliss in a Bottle

Then iOS 13.4 came about. It took me three point releases to realize what had happened (or really, I just happened upon an article). Apple, for some unfathomable reason, decided to allow users to remap the Caps Lock key. One of the options? Escape.

I almost cried.

I immediately went on an search to see if there were any apps that utilized this. I found a few, wasted some money, but then discovered there was a full Vim port called iVim [^1]. I have no idea how they managed it. I didn't think Vim was programmed in a language iOS could consume, but apparently yes? And not only does it work, but you can load a surprisingly large number of plugins [^2], which is incredible-- Vim is a very customizable editor, and this allows me to make it exactly the way I want it. Don't like the colors? You can change those. Want a status bar on the bottom that tells you your word count? Done. So lovely.

## Full integration?

So now I've Vim, actual Vim on my iPad. Yay. 

Now I need to figure out how to actually use it. Typing my stuff in a random buffer doesn't work well unless I can save it somewhere. More importantly, I need to edit my file, the same ones I normally edit on my Mac. After some playing around, I discover something really important about the Files app: Once you "favorite" an app, Files will automatically open that app when you tap on a file that is supported by that app.

Now, take this whole idea of "automatic open" and combine it with a split screen: Files on left, iVim on the right. Tap on a markdown file, and it opens in iVim on the right. This is the _exact_ configuration I use on my Mac. Moreover, I can write my own scripts if I want to [^3].

Friends, I am home.

Moreover, Working Copy exposes all it's file structures to Files. This allows me to access them directly and then, once I'm done, I can push all those changes up easily. Even better: this is exactly how my website accepts new posts. So I can now use my iPad to post to my website easily, and using my favorite editor.

I have only one missing piece, and it's:

## iCloud + Git == Disaster || Bliss

Working Copy allows you to specify "synced folders". These are folders that are synced via the cloud, but should also be git repositories as well. This _should_ allow the best of both worlds. I haven't tried it yet, but my theory is that these synced folders would allow me to edit as I please, then go into Working Copy and save/commit them. If so, it's essentially the last piece of the iOS puzzle for me.

I suspect caveats. 

For instance, there's a good chance those synced folders only sync when Working Copy is actually open. If so, then editing anything from Working Copy within the Files app is asking for trouble. This is manageable; I just need to hide the Working Copy folders from Files (doable).

The second issue: iCloud is notorious for handling git wrong. Git tends to shuffle, move, and edit a lot of files behind the scenes, especially when you commit. All of those changes need to happen or you can corrupt your repository. iCloud does not always handle this well. I've heard horror stories, but I've also heard of successes. I suspect it depends on usage: maybe don't try to sync multiple computers all editing the files at once. But I have only my Mac, my iPad, and my iPhone. Is that too much? I dunno.  

I also already use a different syncing service, one I control, and one I happen to like. When things fail, it gives me actual errors I can use to track down the issue and fix it. If something goes wrong, I can SSH into the server and literally fix the files in question. iCloud is a black magic box that fails silently.

But I'm tempted. I already have 2TB of storage for photos that use maybe a quarter of the space. If I can trust iCloud -- and that is a big honking **if** -- then it would be ideal (a lot of apps support iCloud implicitly). But Apple doesn't have a great record with stuff like this. Yet... I'm tempted, folks, very tempted.

We'll see.

## Conclusion

So now I'm writing this post in Vim on my iPad, something I never thought would be possible. Even more impossible: I'll submit this post with said iPad.

Life is getting better folds; it truly is.

And now that I'm done writing this, perhaps I will go on to work on my book, in an editor I love, on a device I love.


[^1]: There's also an old 'port' simply called Vim. I've seen it before, but it was limited. iVim, in contrast, appears to be not only a full port, but it's also very integrated into iOS.
[^2]: There are some very clear restrictions: Plugins that either depend on underlying subsystems (ex: Java, or whatever) or must build said dependency don't work. There are several a lot of plugins that have to cmake or compile a separate program. Luckily, I don't really use those.
[^3]: And yes, I have done just that in the past. Sometimes, be a software developer is _awesome_.
[^4]: This was frustrating. Dropbox practically created the market for file syncing. And I generally don't mind companies expanding into new markets, it's practically the ethos of tech, but I draw the line when they start forcing their new stuff into my face without any recourse to back out. Okay, cool: you now allow multiple people edit files at the same time. But for all that is holy: I just want to sync. I don't care. Stop invading my space!
