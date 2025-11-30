# Changelog - Recent Fixes

## 🐛 Bug Fixes

- **#50**: [BUG] Cross-project hook inheritance executes sibling project hooks inappropriately (bug, has repro, platform:macos, area:tools)
- **#48**: Claude Code executes wrong project hooks in multi-project workspace (bug, has repro, platform:macos, area:tools)
- **#37**: Invalid JSON Encoding in API Request Body (bug, duplicate, area:core, platform:macos, area:api)
- **#32**: Calling MCP tool create-spec-doc freezes in Cursor AI + GPT-5 (bug, area:mcp, area:ide, external)
- **#25**: Missing Tool Result Block for Tool Use ID toolu_01GUUUdR6TqtrqKTprMSuLqc (bug, duplicate, area:core, platform:macos, area:api)
- **#22**: [BUG] Search/Grep tool is BROKEN (bug, has repro, area:tools)
- **#21**: Invalid JSON Encoding Error During API Request (bug, duplicate, area:core, platform:macos, area:api)
- **#15**: [BUG] Hard to trace changes in releases (bug)
- **#13**: Agent Command Autocomplete Regression in v72 (bug, has repro, platform:macos, area:tui)
- **#12**: [BUG] PowerLevel10k terminal theme causes Claude Code timeout and parsing failures due to ANSI escape sequence contamination (bug, has repro, area:core, platform:macos, area:tui)

## 📚 Documentation

- **#39**: [DOCS] Slash command frontmatter table is misformatted (documentation)
- **#30**: [Docs] Undocumented `statusline` configuration feature (documentation, area:tui)
- **#23**: [Documentation] Claude Code release notes for v1.0.71 is not informative. Need more detailed notes. (documentation, enhancement)

## 🔄 Duplicates

- **#37**: Invalid JSON Encoding in API Request Body (bug, duplicate, area:core, platform:macos, area:api)
- **#25**: Missing Tool Result Block for Tool Use ID toolu_01GUUUdR6TqtrqKTprMSuLqc (bug, duplicate, area:core, platform:macos, area:api)
- **#21**: Invalid JSON Encoding Error During API Request (bug, duplicate, area:core, platform:macos, area:api)

## 📊 Statistics

### Total Issues Processed
- **Total closed issues:** 14
- **Bug fixes:** 10 issues
- **Documentation improvements:** 3 issues  
- **Enhancements:** 1 issue (with documentation label)
- **Duplicates:** 3 issues

### Platform Distribution
- **platform:macos:** 9 issues (64.3%)
- Other platforms: Not specified in remaining issues

### Area Distribution
- **area:core:** 4 issues
- **area:tools:** 3 issues
- **area:tui:** 3 issues
- **area:api:** 3 issues
- **area:mcp:** 1 issue
- **area:ide:** 1 issue
- **external:** 1 issue

### Resolution Patterns
- **Cross-project issues:** 2 issues related to hook inheritance in multi-project workspaces
- **API/JSON issues:** 3 duplicate issues related to JSON encoding errors
- **Terminal/UI issues:** 4 issues related to TUI, autocomplete, and terminal theme compatibility
- **Tool functionality:** 3 issues related to specific tools (Search/Grep, MCP tools)