# My Personal Sublime Preference

This is my personal sublime preference.

## Prerequisites
 1. Sublime Package Installer
 2. Material Theme

## Theme, Color Scheme and Basic Layout
```
"ignored_packages":
[
    "Vintage"
],
"theme": "Material-Theme.sublime-theme",
"color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
"always_show_minimap_viewport": true,
"auto_complete": true,
"bold_folder_labels": true,
"caret_extra_bottom": 3,
"caret_extra_top": 3,
"caret_extra_width": 2,
"caret_style": "solid",
"draw_white_space": "all",
"ensure_newline_at_eof_on_save": false,
"material_theme_small_tab": true,
```

## Typography, Layout & Text Behaviour
```
"font_face": "Ubuntu Mono",
"font_options":
[
    "subpixel_antialias",
    "no_bold"
],
"font_size": 12.0,
"highlight_line": true,
"highlight_modified_tabs": true,
"tab_size": 4,
"translate_tabs_to_spaces": true,
"trim_trailing_white_space_on_save": false,
"wide_caret": true,
"word_wrap": true,
"wrap_width": 120,
"indent_guide_options":
[
    "draw_normal",
    "draw_active"
],
```

## Ruler, Folder and File Exclude
```
"rulers":
[
    72,
    79
],
"folder_exclude_patterns":
[
    ".git",
    "__pycache__",
    "env",
    "env3"
],
"file_exclude_patterns":
[
    ".DS_Store",
    "*.pid",
    "*.pyc"
],
```

## Others
```
"scroll_past_end": false,
"show_full_path": true,
"show_minimap": false,
"find_selected_text": true,
"fold_buttons": false,
"overlay_scroll_bars": "enabled",
"line_padding_bottom": 3,
"line_padding_top": 3,
```