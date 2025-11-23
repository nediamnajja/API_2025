# API_2025
# 🎓 University Specializations API

A Flask REST API with ID-based endpoints for managing university specializations and course items, migrated from name-based to UUID-based structure.

## 🚀 Features

- **ID-based endpoints** using UUIDs instead of names for better reliability
- **Complete CRUD operations** for Specializations and Course Items
- **Flask-Smorest** for automatic Swagger UI documentation
- **Separated resources** with proper blueprint architecture
- **Professional API design** with proper HTTP status codes and error handling
- **Modular structure** with class-based views

## 📚 API Endpoints

### Specializations
| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/specialization` | Get all specializations |
| `POST` | `/specialization` | Create a new specialization |
| `GET` | `/specialization/{id}` | Get a specific specialization |
| `DELETE` | `/specialization/{id}` | Delete a specialization |

### Course Items
| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/course_item` | Get all course items |
| `POST` | `/course_item` | Create a new course item |
| `GET` | `/course_item/{id}` | Get a specific course item |
| `DELETE` | `/course_item/{id}` | Delete a course item |

### Utility
| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/ping` | Health check endpoint |
| `GET` | `/swagger-ui/` | Interactive API documentation |

## 🛠️ Setup & Installation

### Prerequisites
- Python 3.8+
- pip

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/nediamnajja/university-specializations-api.git
   cd university-specializations-api
