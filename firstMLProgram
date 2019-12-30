# 1 = smooth, orange
# 0 = bumpy, apple


from sklearn import tree
features = [[140, 1], [130, 1], [150, 0], [170, 0]]
labels = [0, 0, 1, 1]
clf = tree.DecisionTreeClassifier()
clf = clf.fit(features, labels)

print("This program can identify apples from oranges")
print("Texture is either 'smooth' or 'bumpy'")

weight = float(input("Enter the fruits weight in grams: "))
texture = input("Enter the fruits texture: ")

if (texture == 'smooth'):
    texture = 1
elif(texture == 'bumpy'):
    texture = 0


if (clf.predict([[weight,texture]]) == 1):
    print('The fruit is an orange')
elif (clf.predict([[weight, texture]]) == 0):
    print('the fruit is an apple')



