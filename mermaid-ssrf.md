# Mermaid SSRF Test

\`\`\`mermaid
graph TD
    A[Start] --> B{Decision}
    click A \"http://t1.rebind.beeli.id/mermaid-click\" \"Tooltip\"
    click B \"http://t1.rebind.beeli.id/mermaid-click2\"
\`\`\`
