# NoteekFlow

NoteekFlow is a cross-platform note-taking app built with Avalonia and .NET 10

 ### Current features
- Open a workspace folder and browse nested folders
- Open, edit, and save Markdown, Noteek, and text files
- Switch Markdown notes between editing and rendered preview (the preview is not working properly yet)
- Draw pressure sensitive ink in Noteek files with a stylus, or mouse
- Preview basic image files and PDF pages
- Close editor tabs and switch between open files

Noteek files are JSON with a `version` and an `elements` array. Ink strokes
store ordered points with canvas coordinates and pressure.

UI messages are stored in `.resx` resources under `Resources/`; `Strings.cs.resx`
provides the Czech translation, and additional cultures can be added with the
same resource keys.

