# admin-scms

Static CMS collections and fields for creating and editing collections and fields, for use with basa-casa/admin. Example site includes admin pages `admin/collections/index.md` and `admin/fields/index.md` for quick deployment to your admin.

Use this module alone to create your own library, i.e. yourorg/admin-yourorg, to generate your own custom CMSes. 

## Prerequisites
 - [ ] Hugo ([Installation instructions](https://gohugo.io/installation))

 - [ ] Git ([Installation instructions](https://github.com/git-guides/install-git))

 - [ ] A Hugo site tracked by Git
    ```
    hugo new site my-awesome-site
    cd my-awesome-site
    git init
    hugo mod init github.com/username/my-awesome-site

    # Replacing my-awesome-site with your site directory, and username with yours.
    ```

## Installation

1. Import path `github.com/basa-casa/admin-scms` to your module config.
1. (optional) Copy the examplesite content and data into your project - the index.md files will give you pages at /admin/collections and /admin/fields for creating CMS parts.

## Usage

### Getting Started

1. Run `hugo server`
    
2. Open [http://localhost:1313/admin/collections](http://localhost:1313/admin/collections)

### /admin/collections

Create and manage collections as individual `.yml` files in `/data/scms/collections` for import to any CMS. 

### /admin/fields
Has collections enabled for creating 16 different types of fields as individual `.yml` files in `/data/scms/fields` for import to any collection or parent field. 
