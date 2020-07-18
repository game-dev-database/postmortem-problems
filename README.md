# Dataset of Video Game Development Problems

* [Dataset CSV](dataset.csv)
* [Catalogue of Video Game Problems](catalogue.csv)
* [List of Postmortems](postmortems.csv)
* [List of Game Genres](genres.csv)
* [List of Game Modes](modes.csv)
* [List of Game Platform](platform.csv)

## Related publications

* [Dataset of Video Game Development Problems -- Arxiv](https://arxiv.org/abs/2001.00491)

## Context

Different to traditional software development, there is little information about the software-engineering process and techniques in video-game development. One popular way to share knowledge among the video-game developers' community is the publishing of postmortems, which are documents summarizing what happened during the video-game development project. However, these documents are written without formal structure and often providing disparate information.

This is a grounded dataset describing software-engineering problems in video-game development extracted from postmortems. It was created using an iterative method with which we manually coded more than 200 postmortems spanning 20 years (1998 to 2018) and extracted 1,035 problems related to software engineering while maintaining traceability links to the postmortems.

We grouped the problems in 20 different types. This dataset is useful to understand the problems faced by developers during video-game development, providing researchers and practitioners a starting point to study video-game development in the context of software engineering.

## How to contribute

Contribute with the database creating a `pull request` or an `issue`.

Please, to provide:

* A PDF of your source with your notes highlighted (`postmortems/`);
* The issues you found on the dataset table (`dataset.csv`)
* You can make a `pull request` with problems that are not on the catalog (`catalogue.csv`);
* You may also add more `genres`, `modes`, and `platforms`;
