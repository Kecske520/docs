---
title: Assigning issues and pull requests to other GitHub users
intro: Assignees clarify who is working on specific issues and pull requests.
redirect_from:
  - /articles/assigning-issues-and-pull-requests-to-other-github-users
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

Anyone with write permissions to a repository can assign issues and pull requests.

You can assign up to 10 people to each issue or pull request, including yourself,{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.17" %} anyone who has commented on the issue or pull request,{% endif %} anyone with write permissions to the repository, and organization members with read permissions to the repository. For more information, see "[Access permissions on {% data variables.product.prodname_dotcom %}](/articles/access-permissions-on-github)."

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-issue-pr %}
3. Select the checkbox next to the items you want to assign to someone. ![Issues metadata checkbox](/assets/images/help/issues/issues_assign_checkbox.png)
4. In the upper-right corner, click **Assignee**.
5. To assign the items to a user, start typing their username, then click their name when it appears. You can select and add up to ten assignees to an issue or pull request. ![Issues assignment drop-down](/assets/images/help/issues/issues_assigning_dropdown.png)

### 더 읽을거리

* "[Filtering issues and pull requests by assignees](/articles/filtering-issues-and-pull-requests-by-assignees)"
