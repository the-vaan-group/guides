# Git

A guide for programming within version control.

- Use a good GUI git client, e.g., [GitKraken], [SublimeMerge], or [Tower].
- Write [good commit messages].
- Perform work in [a feature branch][branching].
- Push commits to your branch regularly (at least once per day) as a backup strategy.

## Commit Messages

- Use [imperative present tense][imperative mood] in the subject line

  > _\[If applied, this commit will\]_ Remove deprecated methods
  >
  > _\[If applied, this commit will\]_ ~~Removed deprecated methods~~

- Capitalize the subject line
- Do not end the subject line with a period
- Limit the subject line to 50 characters

## Collaboration

- Avoid including files in source control that are specific to your development
- Avoid merge commits by using a [rebase workflow][merge vs rebase].
- [Rebase][merge vs rebase] your branch frequently to incorporate upstream changes.
- Squash multiple trivial commits into a single commit.
- Delete local and remote feature branches after merging.

## Configuration

- Use [fast-forward rebase] by default instead of merge when you pull remote changes:

  ```
  git config --global pull.ff only
  ```

## Learning Materials

- [How To Deal With Merge Conflicts][merge conflicts]
- [Merge vs Rebase]
- [What Is Interactive Rebase][interactive rebase]
- [How To Undo And Recover From Mistakes In Git][recover from git mistakes]
- [Branching]

### Additional Reading

- [Linus Torvalds On Clean History][linus]

[branching]: https://www.git-tower.com/learn/git/ebook/en/desktop-gui/branching-merging/branching-can-change-your-life/
[fast-forward rebase]: https://blog.sffc.xyz/post/185195398930/why-you-should-use-git-pull-ff-only-git-is-a
[find the pull request]: http://stackoverflow.com/a/17819027
[gitkraken]: https://www.gitkraken.com/
[good commit messages]: https://chris.beams.io/posts/git-commit/
[imperative mood]: https://chris.beams.io/posts/git-commit/#imperative
[interactive rebase]: https://www.youtube.com/watch?v=JkpYvXdbnfQ
[linus]: https://www.mail-archive.com/dri-devel@lists.sourceforge.net/msg39091.html
[merge konflicts]: https://www.youtube.com/watch?v=MK4u5-Lwy5Q
[merge vs rebase]: https://www.youtube.com/watch?v=xot40u-_1FI
[recover from git mistakes]: https://www.git-tower.com/learn/git/first-aid-kit/
[sublimemerge]: https://www.sublimemerge.com/
[tower]: https://www.git-tower.com/mac
