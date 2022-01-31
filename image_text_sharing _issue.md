and sharing multiple images with text to instagram.
Images are sharing but text is not .

* imageList: List of image paths

 await Share.shareFiles(imageList,
          text: "sharetext with images",
          subject: "Sample",
          sharePositionOrigin: box.localToGlobal(Offset.zero) & box.size);
