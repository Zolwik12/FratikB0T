package pl.fratik.commands.system;

import net.dv8tion.jda.api.EmbedBuilder
import net.dv8tion.jda.api.sharding.ShardManager;
import net.dv8tion.jda.api.entities.Member;
import org.jetbrains.annotations.NotNull;
import pl.fratik.core.command.Command;
import pl.fratik.core.command.CommandCategory;
import pl.fratik.core.command.CommandContext;
import pl.fratik.core.command.PermLevel;
import pl.fratik.core.entity.GuildDao;
import pl.fratik.core.util.UserUtil
import pl.fratik.core.entity.Uzycie

public class UsersPerms extends Command {

     public UsersPermsCommand(GuildDao guildDao, ShardManager shardManager) {
        name = "usersperms";
        aliases = new String[] {"userPermLvl"};
        category = CommandCategory.SYSTEM;
        uzycie = new Uzycie("
        this.guildDao = guildDao;
        this.shardManager = shardManager;
        this.embedBuilder = embedBuilder
        allowPermLevelChange = false;
}
