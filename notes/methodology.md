# Methodology Notes

## Evidence Types Considered
- Public posts, comments, and engagement trails
- Multimedia and associated metadata (where available)
- Account artifacts (creation signals, linked identifiers)
- Relationship graph signals (followers/following, shared infra, username reuse)

## Tooling Workflow
- Use SpiderFoot for automated collection + initial pivots
- Use Sherlock for quick username footprint checks across platforms
- Use Maltego to visualize entity relationships and possible clusters
- Document the chain of reasoning, assumptions, and limitations

## Integrity & Documentation
- Keep a structured log of: time, source, query, and output summary
- Preserve original screenshots/exports in `images/`
- Maintain clear labeling of what is confirmed vs inferred
