# Processing Legacy Dependencies

This is repo stores the legacy dependency files used for building Processing.

> [!NOTE]
> This repository directly serves and continuously deploys files to `download.processing.org` using Netlify.

## Purpose
To [build Processing](https://github.com/processing/processing4/blob/main/build/README.md), the legacy build system (Ant) downloads various dependencies, such as OpenJDK and OpenJFX, as specified in the [`build.xml`](https://github.com/processing/processing4/blob/2a97f64607f8d73ff07ccd1c1e7e8b22dffcec40/app/build.xml) file. These dependencies are served at stable URL at `download.processing.org`. This is a fallback as many of those necessary files are longer being hosted by their original distributors.

