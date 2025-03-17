```toml
#!meta - parametric agent block

# Optional - Knowledge files. Can be relative to base_dir, or absolute
# knowledge_globs = ["/some/path/to/knowledge.md"]

# When set, it will create/update files (otherwise, code will be inlined this prompt file)
base_dir = "web"

# Narrow or broaden your context files (by default, most popular languages)
# context_globs = ["**/*.rs", "**/*.html", "**/*.js", "**/*.css"]

# Optional working file for parallelism (advanced)
# input_globs   = ["**/mod.rs"]

# This will layer on top of the aliases defined in the workspace and base config.toml
model_aliases = {claude = "claude-3-7-sonnet-latest", high = "o3-mini-high", low = "o3-mini-low", fast = "gpt-o4-mini"}

# If not set, will use config.toml defined model
# model = "claude"
```

Here you have index.html, script.js, styles.css. Fix responsivness on small devices.

====
> Info: Duration: 2m 56s 111ms | ~$0.0083 | Prompt Tokens: 12,797 (cached: 0) | Completion Tokens: 10,653 (reasoning: 0) | Model: gpt-4o-mini | Adapter: OpenAI


