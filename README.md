# CS 180: Computer Vision and Computational Photography Portfolio

A GitHub Pages portfolio by Sriya Kantipudi for UC Berkeley's CS 180 course.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Then open `http://127.0.0.1:4173/` in a browser.

## Project pages

The homepage cards link to `0/`, `1/`, and `2/`. Put each project's content in the matching numbered directory with an `index.html` entry point.

Project 0 is scaffolded as:

```text
0/
├── index.html
└── media/
    └── README.md
```

Add Project 0 images and videos to `0/media/`, then reference them from `0/index.html` with paths such as `./media/close-up.jpg`. Future project pages can reuse `project.css` for the same layout and typography.

The temporary homepage thumbnails are stored in `assets/project-0.png`, `assets/project-1.jpg`, and `assets/project-2.png`; they can be replaced with screenshots of the finished projects without changing the layout.
