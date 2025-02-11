# Development Journal

## 2024-07-30
- Debugging TemplateDoesNotExist Error:

    Identified missing templates causing the error.
    Created new templates: post_confirm_delete.html, post_detail.html, post_form.html, and user_posts.html.
    Verified the template_name attributes in the views and corrected paths where necessary.

- Code Modifications:

    Modified various Python cache files, models, views, forms, and HTML templates.
    Ensured all modified files are correctly staged for the next commit.

- Challenges:

    Faced issues with the pagination in the blog post listing. Corrected the logic in the template to ensure pagination links render correctly.
    Debugged issues related to missing templates which required careful inspection of the file structure and view configurations.

- New Additions:

    Added several new media files under media/profile_pics.
    Added a JSON file (posts.json) to presumably hold sample post data for testing.

- Next Steps:

    Review all new and modified files to ensure there are no further errors.
    Commit the changes with a detailed commit message.
    Continue testing the application to ensure all functionalities are working as expected.


## 2024-07-29
- Added initial commit of users signals and migrations.
- Updated blog and users models.
- Modified django_project settings and URLs.

## 2024-07-28
- Worked on users profile template.
- Fixed issues related to __pycache__ files.

## 2024-07-27
- Created initial setup for the project.
- Added initial configurations and settings.
