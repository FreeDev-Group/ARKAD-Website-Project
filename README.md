# ARKAD Website Project

Institutional website for ARKAD, developed by FREEDEV using WordPress and hosted on Hostinger.

## Current status

WordPress has been installed and initially deployed on Hostinger.
The ARKAD website itself still needs to be designed and built from scratch on this installation.

The first milestone was approved on October 20, 2026, according to the project information provided by Destin. This approval concerns the initial technical setup and deployment, not a completed website.

This repository currently contains preparation files. Project-specific implementation sources still need to be added.

## Project objectives

- Present ARKAD's identity, mission, activities, and projects.
- Publish approved news, events, and resources.
- Provide official contact and participation information.
- Deliver a responsive, accessible, and maintainable website.
- Allow authorized administrators to update content.

## Requirements and scope

The initial reference is the ARKAD Website Project Proposal & Requirements, prepared by FREEDEV, version 0.1, September 2026.

The document remains a proposal subject to stakeholder confirmation. Its suggested sections are not automatically confirmed deliverables.

Proposed sections:

- Home
- About ARKAD
- Programs / Activities
- Projects / Initiatives
- News / Articles
- Events
- Resources
- Gallery
- Team / Leadership
- Contact
- Participation and support information, where applicable

Final navigation, content, languages, and features must be confirmed with ARKAD.

Payments, advanced registration, member-only features, and external integrations require separate scope confirmation.

## Delivery milestones

### 1. Project structure setup and initial deployment

Initial WordPress installation, hosting setup, and deployment.

Status: approved according to the project information provided by Destin.

### 2. Content creation and integration

Proposed working scope:

- Confirm requirements and prepare the sitemap.
- Define branding and page layouts.
- Build the website on the existing WordPress installation.
- Configure agreed features.
- Collect and integrate approved content.
- Prepare the first complete client preview.

Target date communicated: November 5, 2026.

The interpretation of this milestone as full website implementation should be confirmed with Michael Kent Burns.

### 3. Client review, revisions, and final delivery

- Present the website for client review.
- Record and prioritize feedback.
- Apply agreed revisions.
- Complete final quality assurance.
- Deploy reviewed changes.
- Provide administrator documentation and handover.
- Record final client acceptance.

## Proposed technical approach

The following approach has been recommended but is not yet recorded as implemented:

- CMS: WordPress
- Hosting: Hostinger Web / WordPress hosting through hPanel
- Parent theme: Twenty Twenty-Five
- Project theme: ARKAD child theme named `arkad`
- Editing: native WordPress blocks and Site Editor
- Version control: Git and GitHub

Build on the existing WordPress installation rather than reinstalling it.

Keep project-specific changes in the child theme instead of editing parent theme files directly.

Add plugins only when justified by confirmed requirements.

## Proposed team responsibilities

| Team member | Responsibilities |
| --- | --- |
| Destin Ash | Coordination, requirements, technical guidance, reviews, quality control, and client communication |
| Dieudonné | Theme foundation, templates, navigation, forms, source control, and deployment |
| Evelyne | Content collection, page composition, media preparation, editorial consistency, and administrator documentation |

Both mentees contribute to testing. Destin reviews implementation work.

This allocation does not represent completed GitHub issue assignments.

## Development workflow

1. Confirm scope, sitemap, and content requirements.
2. Review the visual direction and representative page layouts.
3. Prepare a development or staging environment.
4. Build the theme foundation, header, footer, and navigation.
5. Build Home, About, and Contact first.
6. Review these pages before implementing remaining sections.
7. Integrate approved content.
8. Test functionality, responsive layouts, accessibility, and performance.
9. Complete client review, revisions, and final delivery.

Use focused branches and pull requests for file changes.

For changes made through WordPress administration, record the affected pages, templates, settings, and checks performed.

Avoid simultaneous edits to the same page or shared template.

## Repository and security

The current `.gitignore` excludes WordPress installation files by default.
Update it deliberately when reviewed project sources are ready.

Proposed child theme location:

    wp-content/themes/arkad/

This directory is planned; its existence is not implied by this README.

Never commit:

- Production configuration, including `wp-config.php`
- Passwords, API tokens, private keys, or SMTP credentials
- Database dumps and private backups
- Form submissions or personal information
- Logs, caches, or confidential client documents
- Media not approved for public distribution

Site Editor customizations may be stored in the database.
Define an export and review procedure for templates and styles that need to be versioned.

Git does not replace private database and media backups.
A theme export is not a complete website backup.

## Deployment

The Hostinger deployment workflow remains to be verified.

Do not treat the documentation-only repository as a complete WordPress deployment.

Before production deployment:

- Resolve access to the organization repository.
- Preserve unrelated website deployment connections.
- Confirm the deployment branch and target directory.
- Test how files absent from the repository are handled.
- Test deployment on an isolated target.
- Preserve production configuration, uploads, and database content.
- Confirm current private backups and a rollback procedure.

## Delivery checklist

- [ ] Confirmed pages and features are implemented.
- [ ] Organizational content and media are approved.
- [ ] Public placeholders and sample content are removed.
- [ ] Navigation, forms, downloads, and media work.
- [ ] Mobile, tablet, and desktop layouts are checked.
- [ ] Headings, alternative text, labels, and keyboard navigation are reviewed.
- [ ] Known limitations and missing client inputs are documented.
- [ ] Administrator instructions are available.
- [ ] Maintenance and backup responsibilities are clear.
- [ ] Final client acceptance is recorded.
