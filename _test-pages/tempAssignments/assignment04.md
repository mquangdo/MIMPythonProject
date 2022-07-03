
**1.** Môn Tối ưu rời rạc dạy bởi giảng viên X có hai cách tính điểm trung bình môn (TBM) từ các điểm thành phần (chuyên cần, giữa kì, cuối kì) như sau:

Cách thứ nhất TBM = 20%.Điểm chuyên cần + 20%.Điểm giữa kì + 60%.Điểm cuối kì

Cách thứ hai  TBM =  30%.Điểm giữa kì + 70%.Điểm cuối kì

(a) Với dữ liệu đầu vào là bộ ba số dương $(a, b, c)$, em hãy tính điểm trung bình của của sinh viên có bộ điểm đó theo cách tính điểm thứ nhất.

	Input: 9 9 8

	Output:  8.4

(b) Tạo ngẫu nhiên bộ điểm của 20 sinh viên. Trong đó, có hơn 50\% sinh viên đạt điểm cuối kì trên 6. Tính điểm trung bình của các sinh viên đó (theo cách tính điểm thứ nhất) và quy đổi sang điểm hệ A-F.

(c) Với dữ liệu điểm của 20 sinh viên ở ý (b), kiểm tra xem với cách tính điểm nào thì tỷ lệ sinh viên đạt xếp loại từ B trở lên cao hơn.

**2.** (Tic-tac-toe) Viết chương trình đưa ra kết quả của trò chơi  Tic-tac-toe từ dữ liệu đầu vào là một bộ gồm 9 số (chỉ gồm các số 0 và 1). Trong đó, 3 số đầu tiên thuộc hàng thứ nhất, 3 số tiếp theo thuộc hàng thứ hai và 3 số cuối cùng thuộc hàng thứ ba.

    Input: 0 0 0 1 1 0 1 1 0
	Output: Player uses 0' win!

    Input: 1 0 1 1 0 0 1 1 0
	Output: Player uses 1' win!

    Input: 0 1 0 1 0 1 1 0 1
    Output: Draw!

000, 110, 110

101, 100, 110

010, 101, 101


Quy ước: Với những dữ liệu chứa đồng thời dòng (hàng, cột, đường chéo) 0 và 1 thì người chơi nào đi trước sẽ dành chiến thắng.

**3.** Hoàn thành bài tập 5.8 và 5.10 trong sách PythonCrashCourse.

**5.8 (Sách PythonCrashCourse) Hello Admin:** Make a list of five or more usernames, including the name
'admin'. Imagine you are writing code that will print a greeting to each user
after they log in to a website. Loop through the list, and print a greeting to
each user:

- If the username is 'admin', print a special greeting, such as Hello admin,
would you like to see a status report?

- Otherwise, print a generic greeting, such as Hello Jaden, thank you for
logging in again.

**5.10 (Sách PythonCrashCourse) Checking Usernames:** Do the following to create a program that simulates how websites ensure that everyone has a unique username.
- Make a list of five or more usernames called current_users.
- Make another list of five usernames called new_users. Make sure one or
two of the new usernames are also in the current_users list.
- Loop through the new_users list to see if each new username has already
been used. If it has, print a message that the person will need to enter a
new username. If a username has not been used, print a message saying
that the username is available.
- Make sure your comparison is case insensitive. If 'John' has been used,
'JOHN' should not be accepted. (To do this, you’ll need to make a copy of
current_users containing the lowercase versions of all existing users.