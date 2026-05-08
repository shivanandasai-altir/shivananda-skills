# Contributing

Thanks for helping grow the shared skill library.

## Workflow

1. Create a branch
   ```bash
   git checkout -b add-my-skill
   ```

2. Add your skill in a category folder
   ```
   react-patterns/my-new-skill/SKILL.md
   ```

   If you add a new top-level category, update `package.json` too.

3. Keep the skill valid
   - folder name in lowercase
   - `SKILL.md` required
   - `name` and `description` in frontmatter
   - keep helpers and references inside the same skill folder

4. Test locally
   ```bash
   pi -e /path/to/shivananda-skills
   ```

5. Open a pull request
   - keep the change focused
   - ask for review if the skill affects shared workflows

6. Merge to `main`
   - the repo is the source of truth
   - everyone updates with `pi update`

## Conventions

- Prefer reusable, org-wide skills in this repo
- Keep app-specific skills in project repos
- Use descriptive skill names
- Avoid duplicate or overlapping skills
- If you add a new category, update the README too
