Bulletin And Board System - протокол децентрализованного чата с опциональными серверами.

Требования к системе:
1) Если два пользователя в одном сегменте сети и оба онлайн (видят друг-друга) - сообщение должно проходить вне зависимости от состояния остальной сети и серверов как в приватных, так и в групповых чатах.
2) Данные должны быть доступны в том числе после отключения отправителя от сети (например при помощи серверов)
3) Должен быть механизм поиска пользователя по его контактным данным (например телефону) - TODO.
4) Должен быть механизм модерации в групповых чатах (хотя бы и с возможностью отключения в клиенте - типа рекомендаций).
5) Должен, разумеется, быть механизм шифрования как минимум приватных чатов, а, по возможности, и групповых. - TODO

Базовая идея:

Предполагается максимальное использование существующих концепций libp2p и IPFS: сообщения чата, медиа-вложения, а также все описания и архивы представляют из себя файлы|сущности IPFS; протоколы отделяются по применениям на основе выделения протоколов в libp2p.
