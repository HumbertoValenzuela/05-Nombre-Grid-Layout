# 05-Nombre-Grid-Layout
Grid Layout. usando grid: row / column;

```javascript
.contenedor {   
    display: grid;
    /* grid: row / column */
    /* en row 100 arriba auto en medio 100 abajo.  */
    /* en column son 4 calumnas de 25% */
    grid: 100px auto 100px / repeat(4, 25%);
}

.header {   
    grid-column: 1 / 5;
}

.contenido-principal {   
    grid-row: 2 / 3;
    grid-column: 1 / 4;
}
.sidebar {   
    grid-column: 4 / 5;
    grid-row: 2 / 3;
}
.footer {   
    grid-column: 1 / 5;
}
```
