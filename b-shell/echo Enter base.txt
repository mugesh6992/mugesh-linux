echo "Enter base"
read b

echo "Enter height:"
read h

echo "Enter side1:"
read s1

echo "Enter side2:"
read s2

echo "Enter side3:"
read s3

area=$(echo "($b * $h) / 2" | bc)

perimeter=$((s1 + s2 + s3))

echo "area of the triangle: $area"
echo "perimeter of the triangle: $perimeter"