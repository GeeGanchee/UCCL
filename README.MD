# Geotab Inspection Add-In

This repository hosts a static HTML/JS MyGeotab Add-In for vehicle pre-start inspections.

## How to use

1. **Upload to GitHub**  
   Push these files to a public GitHub repository.

2. **Enable GitHub Pages**  
   - Go to your repo's Settings > Pages.
   - Set the source to the `main` branch and `/ (root)` folder.

3. **Get your add-in URL**  
   - It will be something like `https://Geeganchee.github.io/UCCL/`

4. **Register in MyGeotab**  
   - Go to MyGeotab > Administration > System > System Settings > Add-Ins.
   - Add the URL above as the Add-In source.
   - Update the `<meta name="geotab:addin" ...>` tag in `index.html` to match your actual URL.

## Customization

- Add more drivers to the `driverMap` in `index.html`.
- Update checklists in `formTemplates`.
- To POST to a backend, adjust the fetch code at the bottom of the JS.

## Support

See [MyGeotab Add-In SDK](https://geotab.github.io/sdk/add-ins/) for more options.