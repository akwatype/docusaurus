---
id: doc_tutorial_create_model
title: Create model
---

In your project, go to the model editor. 

![Project home page](assets/!projects!Project3.png)

Just click on the model editor button

![Editor button](assets/!projects!menu!model!editor.png)

And you get an empty editor. The editor is split in three columns :
- Files list
- A file's code
- A Projection of an object in the code

![Project home page](assets/!projects!Project3!model_empty.png)

We will start by creating a new file, click on "+ New File" and get the popup as above.

![Create file](assets/!projects!Project3!model_new_file_type.png)

Type a filename and click "+ Add", you will see your file in the list.
Click on the file in the list and you will see the code editor, empty for the moment.

![Empty file](assets/!projects!Project3!model!Store.akwatype.png)

Write an example model 

```graphql
type School {
  students: [Student]
}

type Student {
  firstname: String
  lastname: String
}
```

![File graph projection](assets/!projects!Project3!model!Store.akwatype_1_graph.png)
