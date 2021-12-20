import itertools

def test():
    file=open('C:/Users/Leeyu/Desktop/sfz/sfz2.txt','w')
    date_nums = ['01','02','03','04','05','06','07','08','09','10','11','12','13','14','15','16','17','18','19','20','21','22','23','24','25','26','27','28','29','30','31','01']
    for index in range(0,31):
            date=date_nums[index]
            sex = '0246813579'  # 性别位
            check = '0123456789X'  # 校验位
            other = '0123456789'   # 其它位
            nums = itertools.product(other, other, sex, check)
            # file=open('C:/Users/Leeyu/Desktop/sfz/sfz2.txt','w')
            for num in nums:
                card = date + "".join(num)
                file.write(card)
                file.write('\n')

if __name__ == '__main__':
    test()
