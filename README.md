message_count = 10
for message_count in reversed(range(2, message_count + 1)):
    print('- Анфиса, есть ли новые письма?')
    print('- Непрочитанных писем: ' + str(message_count) + '.')
    print('Я  прочитал одно, и их осталось ' + str(message_count -1) + '.')
print('- Анфиса, есть ли новые письма?')
print('- Одно непрочитанное письмо.')
print('Я прочитал его. И нет больше писем!')
