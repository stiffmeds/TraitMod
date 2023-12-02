# TraitMod

Example mod for custom Across the Obelisk _effect_ traits.

## Usage

1. Clone or fork this repository.
2. Update the references to point to your versions of _0Harmony.dll_, _Assembly-CSharp.dll_, _BepInEx.dll_, _Obeliskial Essentials.dll_ and _Obeliskial Content.dll_. 
3. Update the _RootNamespace_, _Product_, _AssemblyName_ and _Description_ in **TraitMod.csproj**.
4. Rename the `namespace` in `Plugin.cs` and `Traits.cs` to what you set _RootNamespace_ to in step 3.
5. In **Traits.cs**, enter your trait IDs in the _myTraitList_ array.
6. In **Traits.cs**, code effects for your traits in the _myDoTrait_ method.
7. Build the project.

... that's it, I guess?