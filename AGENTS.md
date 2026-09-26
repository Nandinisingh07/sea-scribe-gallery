<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- ORCA uses shared presentational modules in `src/components/OrcaUI.tsx` and dedicated TanStack route files for each feature, because feature content needs independent navigation and metadata.
- Current marine values and maps are explicitly illustrative UI examples, not safety guidance, because no verified live feed is connected.
