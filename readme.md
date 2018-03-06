**- ¿Qué comando utilizaste en el paso 11? ¿Por qué?**
 Para eliminar el último commit junto a sus cambios he utilizado el comando (git resed --hard HEAD ~1), ya que con el --hard se elimina todo lo que hay en el working copy junto al último commit.

**- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
 En primer lugar he usado el comando (git reflog) para encontrar el último commit que había eliminado, y después el comando (git reset --hard más el código del commit) para reestrablecer el último commit borrado.

**- El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?** No.

**- El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?**
 Sí, pero lo solucioné eliminando todo lo que no pertenecía al cambio en styled y creando un nuevo commit.

**- El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?**
 No.

**- ¿Qué comando o comandos utilizaste en el paso 25?**
 He utilizado el comando (git graph).

**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
 Si.

**- ¿Qué comando o comandos utilizaste en el paso 27?**
 (git reset HEAD ~1), para deshacer el merge sin eliminar los cambios en el working copy, ya que no se utiliza el --hard.

**- ¿Qué comando o comandos utilizaste en el paso 28?** 
 (git checkout -- don-quijote.md), para dejar todo como estaba antes.

**- ¿Qué comando o comandos utilizaste en el paso 29?**
 (git branch -D title), la D es con minúscula al principio, pero para confirmar que estamos seguros de la eliminación hay que volver a poner el comando en mayúscula.

**- ¿Qué comando o comandos utilizaste en el paso 30?**
 Primero he utilizado el comando (git reflog) para encontrar el código del último merge, y luego  (git reset --hard más el código del merge) para reestableer el merge.

**- ¿Qué comando o comandos usaste en el paso 32?**
 En este paso he ultilizado en primer lugar el comando (git log) para encontrar el código del primer commit, y más tarde (git reset --hard más el código del commit) para reestablecerlo. 

**- ¿Qué comando o comandos usaste en el punto 33?**
 En este paso he utilizado el comando (git reflog) para buscar en todos los commits que he ido creando, y finalmente (git reset --hard más el código del commit) para reestablecer el último commit.

