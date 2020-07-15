## usersテーブル
|Column|Type|Options|
|------|----|-------|
|email|string|null: false|
|password|string|null: false|

### Association
- has_many :tweets

## tweetsテーブル
|Column|Type|Options|
|------|----|-------|
|image|text||
|text|text||
### Association
- belongs_to :user