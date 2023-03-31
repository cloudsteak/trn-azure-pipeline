# trn-azure-pipeline

Példa repository Azure Pipeline alapú megoldásokhoz

## Git alapok

### Telepítés

https://git-scm.com

### Első beállítás

Furrast le az adott parancsokat az adataiddal

```bash
git config --global user.name "Neved"
git config --global user.email "az@email.címed"
```

### Helyi repo létrehozása adott mappában

```bash
git init
```

### Távoli repository másolása helyi mapppába

```bash
git clone https://github.com/cloudsteak/trn-azure-pipeline.git
```

### Módosított fájlok hozzáadása helyi repohoz

```bash
git add .
```

### Módosított fájlok véglegesítése helyi repoban

```bash
git commit -m "valami szöveg, ami leírja a módosítást"
```

### Módosított fájlok feltöltése a távoli repository-ba

```bash
git push origin main
```
