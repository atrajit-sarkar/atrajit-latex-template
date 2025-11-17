# Atrajit-Pi Theme - Quick Reference Guide

## 📦 Installation & Usage

### Basic Setup
Simply replace your package declaration:

```latex
% Old theme (blue, zeta-based)
% \usepackage{atrajit}

% New theme (warm brown/gold, pi-based)
\usepackage{atrajit-pi}
```

## 🎨 Color Palette

The Pi theme uses an elegant academic color scheme:

- **piPrimary** (Saddle Brown): Main text and borders
- **piSecondary** (Dark Goldenrod): Accents and decorations  
- **piAccent** (Peru): Highlights and ornaments
- **piDark** (Dark Brown): Deep text elements
- **piLight** (Wheat): Subtle backgrounds

## 🔮 Decorative Symbols

### Pi Circle (Main Symbol)
```latex
\picircle    % Hexagonal frame with pi symbol
\pibadge     % Ornamental circular badge with pi
```

## 📝 Theorem Environments

All numbered by section with elegant colored styling:

```latex
\begin{theorem}[Optional Name]
  Your theorem content...
\end{theorem}

\begin{lemma}...\end{lemma}
\begin{proposition}...\end{proposition}
\begin{corollary}...\end{corollary}
\begin{definition}...\end{definition}
\begin{example}...\end{example}
\begin{exercise}...\end{exercise}
\begin{remark}...\end{remark}
\begin{note}...\end{note}
```

## 🎯 Custom Markers

```latex
\todostar        % TODO marker with star icon
\notebell        % Note marker with bell icon
\importantmark   % Important marker with warning icon
```

## 📚 Mathematical Sets

Pre-defined set notation:

```latex
\RR   % Real numbers
\NN   % Natural numbers
\ZZ   % Integers
\QQ   % Rational numbers
\CC   % Complex numbers
```

## 🎪 Text Highlighting

```latex
\mathterm{eigenvalue}      % Bold, primary color - for math terms
\defterm{manifold}         % Italic, secondary color - for definitions
\code{function}            % Monospace, dark color - for code/notation
```

## 📦 Special Boxes

```latex
\keybox{
  Important concept or equation goes here...
}
```

## 🎨 Ornamental Elements

```latex
\sectionbreak   % Decorative section separator with diamonds and pi
```

## 📖 Reference Shortcuts

```latex
\thmref{label}    % References: "Theorem X"
\lemref{label}    % "Lemma X"
\propref{label}   % "Proposition X"
\corref{label}    % "Corollary X"
\defref{label}    % "Definition X"
\exref{label}     % "Example X"
```

## ⚙️ Optional Settings

```latex
\useSubsectionEqNum    % Number equations by subsection
\useRomanSections      % Use Roman numerals for sections (I, II, III...)
```

## 📑 Headers & Footers

The theme automatically provides:
- **Left Header**: Author name in small caps
- **Center Header**: Section | Pi Symbol | Subsection
- **Right Header**: Graduation cap icon
- **Footer**: Ornamental page number with pi decoration

## 🔄 Switching Between Themes

You have two themes available:

| Feature | atrajit (Zeta) | atrajit-pi (Pi) |
|---------|----------------|-----------------|
| Color   | Blue tones     | Warm brown/gold |
| Symbol  | ζ (zeta)       | π (pi)          |
| Style   | Modern/tech    | Classic/elegant |
| Numbering| By subsection  | By section      |
| Biblio  | IEEE style     | Alphabetic style|

## 📄 Files Included

- **atrajit-pi.sty**: Main package file
- **utils-pi.tex**: Visual elements and decorations
- **macros-pi.tex**: Custom commands and shortcuts
- **template-pi.tex**: Sample document demonstrating features

## 💡 Tips

1. The pi theme uses **warmer colors** - perfect for printed documents
2. **Hexagonal frames** give a sophisticated geometric touch
3. Theorem environments have **built-in color coding** by type
4. Footnotes use **pi notation** (π₁, π₂, etc.)
5. List environments have **custom colored bullets**

---

**Enjoy your elegant mathematical typesetting! 🎓**
