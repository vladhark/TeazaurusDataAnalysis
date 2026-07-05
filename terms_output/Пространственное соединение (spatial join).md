# Пространственное соединение (spatial join)

## определение

Операция, сопоставляющая каждому объекту (точке) атрибуты полигона, в который эта точка попадает (предикат within). gpd.sjoin(gdf_points, gdf_polygons, how='left', predicate='within').

