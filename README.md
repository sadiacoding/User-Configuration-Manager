# User-Configuration-Manager

A simple Python-based configuration manager that allows users to add, update, delete, and manage settings efficiently.

## Features

✅ Add new settings  
✅ Update existing settings  
✅ Delete settings  
✅ View all saved settings  
✅ Prevent duplicate setting names  
✅ Easy dictionary-based storage  


## Installation

Clone the repository:

```bash
git clone <repository-link>
```

Move into project folder:

```bash
cd User-Configuration-Manager
```

Run:

```bash
python main.py
```

## Functions

### Add Setting

Adds a new setting.

Example:

```python
add_setting(settings, ("theme", "dark"))
```

Output:

```bash
Setting 'theme' added successfully!
```

---

### Update Setting

Updates an existing setting.

Example:

```python
update_setting(settings, ("theme", "light"))
```

---

### Delete Setting

Removes a setting.

Example:

```python
delete_setting(settings, "theme")
```

---

### View Settings

Displays all current settings.

Example:

```python
show_settings(settings)
```

Output:

```bash
{
   "theme": "dark",
   "language": "english"
}
```

## Example Usage

```python
settings = {}

add_setting(settings, ("theme", "dark"))
update_setting(settings, ("theme", "light"))

print(settings)
```

Output:

```bash
{'theme': 'light'}
```

## Technologies Used

- Python
- Dictionary Data Structure
- Functions

## Future Improvements

- Save settings in JSON files
- GUI support
- User authentication
- Database integration

## Author

Created by: Your Name
