# PracticaGit - Respuestas
Paulina Mujica

--

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque así se deshace el commit, perdiendo incluso la información en el working copy.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

Primero utilicé `git reflog` para saber el codigo del commit recien deshecho y luego usé `git reset --hard 9a9babb `(codigo git eliminado)
para recuperarlo.



--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No me causo ningún conflicto, ya que la rama styled esta por encima de la rama Master.

--
**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Si, me causo conflicto ya que habíamos modificado el mismo archivo en 2 ramas diferentes, entonces se superpuso la información, tuve que ir manualmente al archivo md y borrar la información que pertenecía a la rama htmlify y luego añadir un commit.

--
**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No, porque en la rama master no había modificado nada.

--
**6. ¿Qué comando o comandos utilizaste en el paso 25?**

Primero lo configuré en la configuración global de git con `git config  --global alias.graph “log --graph --decorate --pretty=oneline”` y luego use `git log --pretty=format:"%h%s" --graph` ya que con `git log —graph` no me funconó.

--
**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si, porque la rama tittle solo esta un commit por delante de la rama master y forma una lista hacia abajo.

--
**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` 

--
**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout -- don-quijote.md` 

--
**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D tittle` 

--
**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog` y `git reset --hard codigo merge desecho` 

--
**12. ¿Qué comando o comandos usaste en el paso 32?**

`git reflog` y `git checkout codigo commit inicial` 

--
**13. ¿Qué comando o comandos usaste en el punto 33?**

`git reflog` y `git checkout codigo commit final` 
