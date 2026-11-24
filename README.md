# CALCULADORA-
This repository is a simple calculator project created to practice using Git and GitHub workflows.
def suma(a, b):      devuelve a + b
 
 
def main():      print("=== Calculadora sencilla ===")      a = float(input("Primer número: "))      b = float(input("Segundo número: "))      print(f"Suma: {sumar(a, b)}")
 
 
if __name__ == "__main__":      main()



# 1. Actualizar main  git checkout main  git pull  git status
 
# 2. Crear la rama  git checkout -b potencia  git branch
 
# 3. Editar DemoGit/demo.py (agregar la función potencia) y guardar con Ctrl + S
 
# 4. Probar  Python DemoGit/Demo.py
 
# 5. Revisar cambios (salir de git diff con q)  git status  git diff
 
# 6. Guardar el cambio  git add DemoGit/Demo.py  git commit -m "Agrega función potencia"
 
# 7. Subir la rama  git push -u origin potencia
 
# 8. En GitHub: Comparar y solicitar extracción > Crear solicitud de extracción > Fusionar solicitud de extracción > Confirmar fusión
 
# 9. Actualiza tu copia local y limpia  git checkout main  git pull  git branch -d potencia
 
# 10. Verificar  git status
