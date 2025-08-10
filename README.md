### Ayubowan/Hello! 👋

```bash
> #=> Hi , I'm Nayantha Nethsara ,
> pwd
> srilanka/colombo
> cat info.bla | grep about
> about: A computer science & open source enthusianst.
```

# Minesweeper Game

<p align="center">
  <img 
    src="https://minesweeper-git-backend.vercel.app/api/grid" 
    width="600" height="600" 
    style="border-radius: 8px;" 
    alt="Minesweeper Grid" />
</p>

## How to Play

Click the links below to reveal cells on the Minesweeper grid.

### Grid Controls

<table align="center" style="border-collapse: collapse;">
  <!-- Generate 10x10 cells -->
  <!-- Each cell is a link to reveal that position -->
  <!-- Cell size and styling minimal for markdown -->
  ${
    Array(10).fill(0).map((_, y) => `
    <tr>
      ${
        Array(10).fill(0).map((_, x) => `
          <td style="padding: 4px; border: 1px solid #ccc; text-align: center; width: 24px; height: 24px;">
            <a href="https://minesweeper-git-backend.vercel.app/api/reveal?x=${x}&y=${y}" target="_blank" rel="noopener noreferrer" style="text-decoration: none; font-size: 18px;">⬜</a>
          </td>
        `).join("")
      }
    </tr>
    `).join("")
  }
</table>

---

**Note:** Replace the domain with your live deployed API domain if different.

---

