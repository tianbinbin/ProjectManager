
workspace 'ProjectManager'
platform :ios, '8.0'

# App project
project 'A_Project/A_Project.xcodeproj'

# Framework project
project 'B_Project/B_Project.xcodeproj'


# 添加 Spec 时建议按照字母A-Z排序，便于确认是否已经添加
target 'A_Project'  do
    project 'A_Project/A_Project.xcodeproj'

    # 公开库
    pod 'AFNetworking', '3.2.1'

end

# B_Project 需要引用的 Pods
target 'B_Project' do
    project 'B_Project/B_Project.xcodeproj'

    # 公开库
    pod 'Masonry', '1.0.1'

end

