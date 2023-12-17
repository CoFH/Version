## CoFH Core Changelog
This changelog goes back to the most recent semver consistency adjustment and is not comprehensive of the entire mod's history.
## 1.19.2

### 10.3.0
_Changed_
- Lots of backend changes and adjustments.

_Fixed_
- Adjustments to Overlay Message Handling to work properly on all server types.
- Fixed an issue with slots voiding items in certain circumstances.
- Packets have some extra null checks.

### 10.2.1
_Fixed_
- Fixed an issue with FluidIngredient NBT serialization.

### 10.2.0
_Added_
- All CoFH GUIs now support JEI's Ghost Items where appropriate.
- Cold Resistance Mob effect
	- This prevents the Chilled effect as well as Freeze accumulation and damage.
- Units such as "RF", "mB", "RF/t", etc. can all be localized.

_Changed_
- The Chilled effect has been changed. It reduces move speed (10%), attack speed (20%), look speed (~20%), and applies the Freezing effect if you are not wearing insulated armor.

### 10.0.2
Happy Holidays!

_Fixed_
- Corrects for an infrequent race condition during registration.
- Minor bugfix involving item storages.

### 10.0.1
_Fixed_
- Small correction to config logic to prevent an infrequent client error.

### 10.0.0
_Changed_
- Semantic Versioning consistency adjustment - every new Minecraft version is a "major" release. We did the math retroactively.

## 1.18.2

### 9.2.2
_Fixed_
- Adjustments to Overlay Message Handling to work properly on all server types.
- Fixed an issue with slots voiding items in certain circumstances.
- Packets have some extra null checks.

### 9.2.1
_Fixed_
- Fixed an issue with FluidIngredient NBT serialization.

### 9.2.0
_Added_
- All CoFH GUIs now support JEI's Ghost Items where appropriate.
- Cold Resistance Mob effect
	- This prevents the Chilled effect as well as Freeze accumulation and damage.
- Units such as "RF", "mB", "RF/t", etc. can all be localized.

_Changed_
- The Chilled effect has been changed. It reduces move speed (10%), attack speed (20%), look speed (~20%), and applies the Freezing effect if you are not wearing insulated armor.

### 9.1.2
Happy Holidays!

_Fixed_
- Minor bugfix involving item storages.

### 9.1.1
_Fixed_
- Small correction to config logic to prevent an infrequent client error.

### 9.1.0
_Changed_
- Lots of backend refactors; code structure unification with 1.19.x (10- branch) where possible.

### 9.0.0
_Changed_
- Semantic Versioning consistency adjustment - every new Minecraft version is a "major" release. We did the math retroactively.
