---
layout: page
title: General
menus:
  projects_customizing:
    weight: 1
---
The General category provides controls for the most top-level elements for how a project is registered and displayed across the system.

## Title

![Title Bock](/docs/assets/projects/title-block.png)

### Title

Use this field to update the project title, which displays on the project library and landing pages, as well as associated navigation menus. This field cannot be left empty.

### Subtitle

Use this field to add or update the project subtitle, which displays alongside the primary title. This field is not required.

### Slug

A URL slug describes the exact address of a project on a Manifold instance. In the following example, `the-lab-book` is the slug for a project of the same name on the University of Minnesota Press's instance. The system will automatically create a slug for each new project based on the project title. You can use this field you can adjust the slug as needed.

```html
https://manifold.umn.edu/project/the-lab-book
```

<div style="background: #d4f2ff; margin: 20px 0; padding: 15px;">
<strong>Note</strong>. Adjusting the project slug will affect the URLs for resources that are a part of the project. Manifold will automatically resolve these for links within the system, but if you have shared a URL to a resource outside of Manifold it will need to be updated; otherwise, readers clicking the old link will be directed to a 404 Error Page.
</div>

## Visibility

![Visibility Bock](/docs/assets/projects/visibility-block.png)

### Draft Mode

For use when wanting to load and edit a project and its materials before publishing it for a broad readership. When toggled on, projects are only visible to users logged in with Administrator, Editor, or Marketeer roles—and to Project Creators on projects where they have `Can Modify Project` permissions. New projects are set to Draft Mode by default, and Draft status is denoted in the project library, as well as on the project landing page.

When a project is in Draft Mode, users who have permissions to view the project may annotate, highlight, and even share texts that are part of the project. Links shared on Twitter will only work for those who also have permission to access the project and are logged in. All annotations, comments, and highlights will persist with the project's text when Draft Mode is toggled off.

Determining when drafts are made public falls to the discretion of publishers. You can learn about published texts [in this section](/docs/projects/customizing/texts.html#published-texts), or for an overview check the recommendations for [publishing workflow](/docs/publishing/workflow.html).

<a name="featured"></a>
### Featured

Featured projects take pride of place on the home page in a section of the library all of their own. Only four projects display in this section at a time. If more than four projects are toggled to be featured, only the four most recent will show. By default, new projects are *not* set to be featured.

<div style="background: #d4f2ff; margin: 20px 0; padding: 15px;">
<strong>Note</strong>. If <a href="/docs/projects/collections.html">Project Collections</a> are being employed, the Featured Projects blade will not appear. But projects marked as being Featured can be sorted into a Smart Collection. See the <a href="/docs/projects/collections.html#smart-collections">Collections</a> section for more.
</div>

## Social

![Social Bock](/docs/assets/projects/social-block.png)

### Hashtag

This field is a means to suggest a hashtag to those interested in discussing a project in social media. Include the hashmark (`#`) with the tag, and it will appear in the lower left part of the header on the project's landing page. See the [Social](/docs/projects/customizing/social.html) section for instruction on how to pull Tweets using the hashtag into the project's [activity](/docs/projects/customizing/activity.html) feed.

### Facebook ID

This field allows you to associate a Facebook account with the project. Enter the Facebook username (*without* the `@` sign) or the numeric ID associated with the account, and a link the Facebook account, in the form of the Facebook `f` icon, will appear over the lower left of the Hero image.

### Twitter ID

This field allows you to associate a Twitter account with the project. Enter the Twitter username (with *or* without the `@` sign) and a link to the Twitter account, in the form a Twitter bird icon, will appear over the lower left of the Hero image.

Tweets from this account will not automatically appear in the Recent Activity pane on the project's landing page. But that functionality is possible through the settings in the [Social section](/docs/projects/customizing/social.html).

### Instagram ID

This field allows you to associate an Instagram account with the project. Enter the Instagram username (*without* the `@` sign) and a link to the Instagram account, in the form of the Instagram icon, will appear over the lower left of the Hero image.

## Other

![Other Bock](/docs/assets/projects/other-block.png)

### Publication Date

A publication date is required by the system to [generate citations](/docs/reading/sharing.html)). The date input here refers to the project as a whole (versus individual texts contained within the project) and will be superseded by a publication date associated with specific texts).

<a name="subjects"></a>
### Subjects

Subjects provide a means to categorize projects, which readers can use as filters to sort through the collection of projects on the landing page (see [Projects Library](/docs/reading/library.html)).

Subjects can only be created by users with Administrator roles. All other roles that can access the backend can only select from the list of subjects already loaded into the system. To associate a subject with a project, simply begin typing in this field, and the system will populate those subjects in the system that most closely resemble what you are typing. Once accepted the Subject name will appear beneath the `Add a Subject` field alongside any others that have been associated with the project.

To learn more about how to create Subjects as an Administrator, see the [Subjects section](/docs/customizing/settings.html#subjects). And to see how Subjects can be used to curate Smart Collections, visit the [Project Collections](/docs/projects/collections.html#smart-collections) page.

<a name="tags"></a>
### Tags

Unlike Subjects, Tags can be created by any user who has permission to modify a project and can be used to add further richness to the existing subject classification. Like Subjects, the Tag field provides a helper so that as you begin typing any similar tags that have already been created on your instance will be revealed.

To see how Tags can be used to curate Smart Collections, visit the [Project Collections](/docs/projects/collections.html#smart-collections) page.

<a name="thumbnail"></a>
### Project Thumbnail

This table allows you to modify or customize the avatar representing the project, which displays in the library on the landing page. If no custom avatar has been added to the system, the default icon—made up of eye glasses, a dialog bubble, and a pencil—shows in the left panel.

You can adjust the color of the default icon by selecting from one of the six preset options in the middle panel labelled `Default`.

You can also upload (as a JPEG, TIFF, GIF, or PNG) a new avatar using the right panel labeled `Custom`.

When no text has been added to the `Published` category (see the [Text](/docs/projects/customizing/texts.html) section) the avatar will display as a square, and custom avatars should be prepared accordingly in a 1:1 ratio. If there is a Published Text, you can upload the cover into the `Custom` panel, and it will display according to the dimensions it was prepared.

All custom uploads should be no less than 400px along their shortest dimension.
