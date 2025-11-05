# Exemple de Markdown amb Taules i Blocs de Codi

Aquest fitxer mostra com fer taules amb diferents alineacions i com escriure codi amb ressaltat.

---

## Taula amb alineacions

| Nom            | Rol                  | Punts |
|:---------------|:--------------------:|------:|
| **Anna**       | *Desenvolupadora*    | 95    |
| **Marc**       | *Dissenyador*        | 88    |
| **Laia**       | *Gestora de projecte*| 100   |

- `:----` -> alineació a l’esquerra  
- `:---:` -> alineació centrada  
- `----:` -> alineació a la dreta  

---

## Exemple de blocs de codi

### Codi en **JavaScript**
```javascript
function saluda(nom) {
  console.log(`Hola, ${nom}!`);
}
saluda("Món");
```


### Codi en **Markdown**
```markdown
# Exemple de títol

**Negreta**, *cursiva*, i [enllaç](https://iedib.net)
```

[Inci](./README.md)
