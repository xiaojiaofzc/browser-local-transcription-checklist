# Browser-Local Transcription Page Checklist

## 1. File path

- [ ] The page makes clear that the visitor selects a local audio or video file.
- [ ] The implementation does not upload the selected file to the site's own server.
- [ ] Any model download is described separately from the selected-file path.
- [ ] The page does not imply that a pasted social-media URL is supported unless that flow is implemented and tested.

## 2. Result path

- [ ] A completed transcript can be read in the page.
- [ ] Copying the transcript is tested in the target browser.
- [ ] Downloading the transcript creates a text file and is tested in the target browser.

## 3. Limits

- [ ] Supported input language is named only when the implementation limits it.
- [ ] File-type language matches what the browser and page actually accept.
- [ ] Duration and file-size copy distinguishes a page-set limit from a browser or device limit.
- [ ] The page tells visitors to keep the tab open when processing depends on an active browser tab.

## 4. Privacy copy

- [ ] Privacy copy identifies where selected files are processed.
- [ ] The page does not claim deletion, retention, or non-collection practices that are not evidenced by the implementation or policy.
- [ ] The page does not turn model download behavior into a claim that the selected file was uploaded.

## 5. Claims to avoid unless independently substantiated

- [ ] Accuracy percentages.
- [ ] Universal support for every browser, codec, or file size.
- [ ] Claims that a user can download a social-media video when the page only accepts an already-saved file.
- [ ] Claims that all processing completes offline when the page retrieves a model or other dependency from the network.

## 6. Before publishing

- [ ] Test one real local file end to end.
- [ ] Test copy and text-file download.
- [ ] Check the narrow mobile layout for horizontal overflow and tappable controls.
- [ ] Re-read every visible limitation after the test.

