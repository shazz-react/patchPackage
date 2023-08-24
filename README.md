1. Install package

   - npm i patch-package

2. Make changes

   - Open node_modules, make the changes in the library.

3. Create a .patch file

   - npx patch-package package-name

4. Add below script in package.json "scripts"

   - "postinstall": "patch-package"

5. Run the project
