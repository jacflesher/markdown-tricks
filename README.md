# markdown-tricks

Here are the different types of alerts you can use in GitHub, along with their purpose and syntax:

*   **NOTE**: Highlights useful information that users should know, even when skimming.
    ```markdown
    > **⚠️ NOTE**  
    > Useful information that users should know.
    ```
*   **TIP**: Provides helpful advice for doing things better or more easily.
    ```markdown
    > **⚠️ TIP**  
    > Helpful advice for doing things more efficiently.
    ```
*   **IMPORTANT**: Indicates crucial information necessary for users to succeed.
    ```markdown
    > **⚠️ IMPORTANT**  
    > Key information you need to know to complete this step.
    ```
*   **WARNING**: Demands immediate user attention due to potential risks or to avoid problems. (This is similar to your example but with a standardized GitHub rendering).
    ```markdown
    > **⚠️ WARNING**  
    > Urgent info that needs immediate user attention to avoid problems.
    ```
*   **CAUTION**: Advises about risks or negative outcomes of certain actions.
    ```markdown
    > **⚠️ CAUTION**  
    > Advises about potential negative consequences.
    ```

To use these alerts, the first line must be exactly as shown (case-sensitive for the alert type), followed by your content in a standard blockquote.

Beyond these structured alerts, you can also use general Markdown formatting for emphasis:

*   **Headings**: Using different levels of headings (`#`, `##`, `###`, etc.) can break up text and make important sections stand out.
*   **Bold and Italic Text**:
    *   `**Bold text**` or `__Bold text__` for strong emphasis.
    *   `*Italic text*` or `_Italic text_` for emphasis.
    *   `***Bold and italic text***` or `___Bold and italic text___` for combined emphasis.
*   **Strikethrough**: Using `~~Strikethrough text~~` can indicate outdated or incorrect information.
*   **Code Blocks and Inline Code**:
    *   Using backticks (`` `inline code` ``) for inline code or triple backticks (```` ``` ````) for code blocks can highlight specific commands, file names, or code snippets.
*   **Emojis**: As in your example, strategically placed emojis (like 💡, ❗️, ❌, ✅) can add visual cues and draw the eye to specific points, even outside of the alert syntax.
