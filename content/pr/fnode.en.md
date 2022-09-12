---
title: "FNode"
heroimage: "/img/hero/fnode.jpg"
lightgallery: true
tags: ["programming"]
summary: "Node-based tool for automated file management and visual programming"
thumbnail: "thumbs/fnode.jpg"
apps: "C#, Godot"
gradientcolor: "aqua"
featured": true
weight: 10
---

{{< project id="fnode" name="Node-based process automation" apps="C#, Godot" gh="SimonStorlSchulke/FNode" exe="https://github.com/SimonStorlSchulke/FNode/releases/latest">}}

FNode is a node-based tool for automated file management and visual programming. Using logically linked building blocks, complex actions can be programmed and applied to any file.

{{< image src="/pr/image/fnode_transp.png" title="Nodes">}}

**On the basis of logically linked nodes, FNode offers the following features, among others**
- Automated processing of large amounts of files
- Reading of online APIs for use in the nodetree
- File operations (rename, move, copy, create text files etc.)
- Conversion of image files based on dynamic rules and simple batch processes for image files
- parallel processing of any number of nodetrees

<br>

Simple video example where all PNG files in a folder are converted to WebP.

<video width="100%" muted controls>
  <source src="/pr/res/fnode-1.webm" type="video/mp4">
</video>

<br><br>

## Aber warum?

{{<twoculumn>}}
{{<left 48>}}
In my work at yoose3D, we often have to handle large amounts of files. For example, animations are rendered as multiple layers of image sequence and later stitched together to create the final video. To automate repetitive file management tasks, I built the tool **[y3D-FM (yoose3D File Manager)](https://github.com/SimonStorlSchulke/y3D-FM)**, which renames, moves, and performs image processing on files based on predetermined rules.  
However, since the tool was specifically tailored to tasks at yoose3D and moreover every additional feature further bogged down the UI, I felt the need for a more general tool for automated file management. Since I like to work node-based myself, I looked around for node-based tools for this and didn't find what I was looking for.  
Since I wanted to deal with parsing NodeTrees for a long time, I built one myself.
{{</left>}}
{{<right 48>}}

{{< image src="/pr/image/fnode/y3d-fm.png" title="y3d-fm">}}

*y3d-FM Renaming and Batch-Processing Tool for yoose3D*

{{</right>}}
{{</twoculumn>}}

<br><br>
## More examples

{{< image src="/pr/image/fnode/thumbnailgenerator.png" title="Thumbnailgenerator">}}

*Thumbnail generator that generates square thumbnails from all input images. Many nodes and inputs are documented directly in the software via mouse hint.*
<br><br><br>

{{< image src="/pr/image/fnode/folderinfo.png" title="Folderinfo">}}

*NodeTree to create a text file with information about a folder.*

<br>

## Download
The latest version (currently Windows only) can be downloaded <a href="https://github.com/SimonStorlSchulke/FNode/releases/latest">here at Github</a>.

{{< /project >}}

<style>
  .project-summary h1 {
    font-size: 38px;
  }

  .project-summary img {
  }
</style>
